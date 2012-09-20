Hey and welcome to our wpa2 crack.

To start with, this can only run from POSIX systems.

You will need to install some programs.

apt-get install airmon-ng

apt-get install airodump-ng

apt-get install aireplay-ng

apt-get install aircrack-ng

or you can run live Backtrack from a USB. (http://www.backtrack-linux.org/tutorials/usb-live-install/)



Now you copy the script somewhere on your computer/live installation in a file


create a folder in root called crackcap


then do a nano (filepath of the script) here you will have to edit this part of the code to what ever .txt 

aircrack-ng ./crackcap/capture-01.cap -w (your .txt with password) 


then you make a chmod +x (filepath of the script)

Furthermore you will need to create a .txt file with the password of the WPA2 network you are trying to crack


(Remember this is done in a controlled enviroment)

Type crackwpa2, follow the instruction, and enjoy :D