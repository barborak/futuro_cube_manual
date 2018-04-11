## Variables

PAWN scripts can access persistent variables where, for example, some game progresses and other usefull information can be stored.   

Each variables are identified by its name. Different scripts can access variable of the same name. If the script is using scoring information, variable is identified by name and script hash, which makes it completely unique. No other script can access this variable or imitate its content. 

PAWN API is designed allows to store variable infinite times as often as needed. Underlying structure stores the variable into non-volatile memory only when really necessary. Those cases are usually loosing power of battery and simply request from another script to use differently name variable. 

**Limits:**

* Maximum size of single variable is **501 cells, which is 2004 bytes**. There is no need to use all the space, but it is always available. 
* One script is allow to use only 1 variable and the script needs to register it in code. 
* Variable become inactive, if there is no uploaded script in the cube, that has its registartion. 
* Maximum 10 active variables is allowed.

When the variable is automatically erased or mark as non-existing:

* If there is no script with registration in memory, variable will be probably erased  







   





For details about how to use them, please refer to the [animated Rubiks example](examples/animated-rubiks.md) and to the documentation of APIs related to variables.

