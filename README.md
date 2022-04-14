Step 1 - Installing FiveM Server.
=====================================
easily install the fivem server with a single command.
--------------------------------------------------------
`sudo wget -O vpsservice.zip https://github.com/nugitv/vpsservice/archive/stable.zip && unzip vpsservice.zip && ./vpsservice*/games/fivem/installer.sh`
------------------------------------------------------------------------------------------------------------------------------------------------------

Step 2 - Enabling txAdmin
===========================
To get started, enable txAdmin which should restart the server with the changes made.
-----------------------------------------------------------------------------------------
`sudo fivem_txadminenable`
--------------------------
Now txAdmin has a passcode associated with it when setting up the panel initially, please run the following command to access the direct console of the fivem server and extract the passcode.
--------------------------------------------------------------------------------------------------------------------------------
`sudo tmux a -t FiveM_Server`
----------------------------------
Step 3 - Accessing txAdmin
==========================
During this process do not try to restart or run any commands critical to changing any fivem server related data.
----
Please head over to http://ip_address:40120 to access the control panel.
---------

Step 4 - Linking cfx.re account
==============
Accessing the first page that loads up, please enter the Passcode mentioned above into the input field shown below.

![photo](https://i.imgur.com/RhPJljd.png)
___________________________________________
Once done hit LINK ACCOUNT to proceed, the following action will redirect you to fivem webpage where you need to hit Authorize in order to allow txAdmin to verify that you are in fact the owner of the cfx.re account.
---------------------------------------------------------------
Next it will redirect back to the txAdmin page where a backup password is requested, enter the backup password twice and then proceed.
--------------------------------------------------------------------------------
Step 5 - Completing Setup
==========================
These are the final stages required to complete txAdmin setup. Upon arriving at the following page on the first prompt hit NEXT to continue.
-------------------------------
![photo2](https://i.imgur.com/Ld8lyfS.png)
_______________________________________
The second prompt should ask for a server name to be assigned onto, please enter your desired name and hit NEXT.
-----
The third prompt is a very crucial part of the setup so please listen carefully and do as said, firstly select Local Server Data as the option and hit NEXT.
------
Add the path to the local server data directory as "/var/fivem" and hit NEXT.
-----
The configuration file should be automatically detected, DO NOT CHANGE the file path and only hit NEXT.
-----
![photo3](https://i.imgur.com/EidOPe8.png)
_____________________________________________
Step 6 - Starting up txAdmin
==============================
Click on SAVE AND START the server and it should save in all the configuration details and successfully load in the control panel.
--------------------
![photo4](https://i.imgur.com/AZoLAri.png)
__________________________________________
Congratulations you should now be able to access and use the txAdmin control panel for your fivem server!
-----
