# 6.4 Starting scripts in the standard way 

During debugging all scripts can be started by shell commands. But at regular run, there are differences for MyCube and scripts in FLASH. MyCube is special case, it has dedicated start. And it is repeating MENU GESTURE in GAME MENU. On the other hand, scripts in FLASH can have their own designed icon placed at specific side and menu, plus they can have their own sounds for name and explanations. It is achieved by adding ICON information into the script text file, which is compiled and later parsed by the cube and automatically set up in the menu. For details how to use look at the ICON\(\) function in API. In case no ICON is defined for the script resides in FLASH, there will appear new icon in BLUE MENU instead of CONNECT GAME, which will then starts the script by selecting it in standard way. From FW 4.5 at multiple scripts enviroment is situation slightly different. Scripts, that has no ICON defined are place in extra WHITE menu with dice symbols 1 to 6.
