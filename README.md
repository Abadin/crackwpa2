Hey and welcome to our wpa2 crack.

To start with, this can only run from POSIX systems.

You will need to install some programs.

apt-get install airmon-ng

apt-get install airodump-ng

apt-get install aireplay-ng

apt-get install aircrack-ng

or you can run live Backtrack from a USB. (http://www.backtrack-linux.org/tutorials/usb-live-install/)

mkdir /root/crackcap

mkdir /root/dictionary

make a .txt file inside the /root/dictionay containing the password of the wpa2 router you wish to crack or start browsing the internet for password dictionaries.

run from terminal "nano /usr/sbin/your own name of the program"

copy paste the script code in to the nano

Ones you have copy pastet the script you will have to change this part of the script 
aircrack-ng ./crackcap/capture-01.cap -w (your .txt with password)

then you make a chmod +x "/usr/sbin/your own name of the program"

(Remember this is done in a controlled enviroment)

Type "your own name of the program", follow the instruction, and enjoy :D