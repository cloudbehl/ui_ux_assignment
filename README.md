Project Details:
=======================

index.html and system.html are the two html files that have all the functionality, in order for them to run properly please clone this repository and run the html files locally.

There are Two HTML Pages:
1: DashBoard.
2: Details Of Host.

Dashboard

1. This page List all the Connected Hosts and the values are stored in Table. The Table has 5 Attributes(Connected Hosts,RAM usage,Disk Usage, Network Health, Overall System Health.

2. Random Values are generated For Every Connected Host. 

3. The Green and Red color in rows shows the Status of Each Host whether the Status is Up or Down. 


Details Of Host:

1. On clicking the Host the 2nd Html page will open and  it will show the name of Host which i have passed with the URL or the Host.

2. The Top most division of the Html Page has:
	* The Webserver is up or down.
	* The DataBase is up or Down.
	* For Logged In Users and Logged in User as Admin the random value is being generated.
	* I/o Wait time For the server.

3. The Next Section of Page Shows the Overall System Health. The random value Graph Will  show the Overall Health of the System for Past few Hours and panel is provided with appropriate color and Text.

4. The Next Section is divided into 4 and all sections have a Gauge Chart showing detailed information about the usage of every system.

5. The Last Section has two parts(CPU usage/Disk Usage) is having the proccessing Bars which shows how much memory is being used by Each Core in CPU usage and also memory used by each attribute of Disk Usage(/var Usage,/boot Usage,Swap Usage).

Tested with:
Firefox 41.0.1
Chrome 46.0.2490.80
