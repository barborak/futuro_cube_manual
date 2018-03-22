# Communication - example for 2 cubes
This example shows how 2 cubes can communicate with each other.
...The making is still in progress, further description will be added.

```
#include <futurocube>

#define I1   0xFF000000 //icon colors
#define I2   0x00FF0000
#define I3   0x0000AA00

new icon[]=[ICON_MAGIC1,ICON_MAGIC2,2,1,I1,I2,I1,I2,I2,I2,I3,I3,I3,''cge_n_SPACE'',''cge_n_SPACE'',ICON_MAGIC3,''SPACE_ALERT'',3,2,0] //icon settings

receive(){ //receiving cube
	new data[54]
	while(1){
		Sleep(200);
		if (IsRadioMsgReadable()){
			printf("message received\r\n")
			cellset(data,0x00)
			if (RadioMsgRead(data)){
				//...
			}
			else printf("error while reading\r\n")
		}
		if (RadioIsLost()) break;
	}
	printf("process over\r\n")
}

send(){ //sending cube
	//...
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
