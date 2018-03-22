# Communication - example for 2 cubes
This example shows how 2 cubes can communicate with each other. When the app starts, it waits until a connection with another cube is made. If the connection is successful, each cube gets a role - either transmitter or receiver. The transmitter sends a message ("Hello") each time its side is tapped. The receiver plays a sound every time it gets a message. If the cube is connected to shell, it prints the information about its actions.

```
#include <futurocube>

#define I1   0xFF000000 //icon colors
#define I2   0x00FF0000
#define I3   0x0000AA00

new icon[]=[ICON_MAGIC1,ICON_MAGIC2,2,1,I1,I2,I1,I2,I2,I2,I3,I3,I3,''cge_n_SPACE'',''cge_n_SPACE'',ICON_MAGIC3,''SPACE_ALERT'',3,2,0] //icon settings

receive(){ //instructions for receiving cube
	new data[20]
	while(1){
		Sleep(200);
		if (IsRadioMsgReadable()){
			printf("message received\r\n")
			cellset(data,0x00)
			if (RadioMsgRead(data)){
				Play("drip")
				printf("I received: %s\r\n", data)
			}
			else printf("error while reading\r\n")
		}
		if (RadioIsLost()) break;
	}
	printf("process over, lost connection\r\n")
}

send(){ //instructions for sending cube
	RegAllSideTaps()
	new motion=0
	while(1){
		Sleep(200)
		motion=Motion()
		if(motion){
			new message[5]
			message="Hello"
			if (RadioMessage(message)) printf("message sent\r\n")
			AckMotion()
		}
	}
}

main()
{
	ICON(icon)
	RadioSetBinary()
	RadioInit("COMMUNICATION");
	printf("order: %lu\r\n",RadioGetOrder());
	printf("session id: %lu\r\n",RadioGetSessionID());
	if (RadioGetOrder() == 0) {
		printf("I am the transmitter.")
		send()
	}
	else {
		printf("I am the receiver.")
		receive()
	}
}
```
