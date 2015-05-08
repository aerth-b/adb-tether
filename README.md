# android-debian-usb-tether

Using adb, tetherbot.apk, and SOCKS. Python + curses interface

This script makes using Tetherbot easier. Tetherbot shares internet from android to debian via usb, but requres some command lines that are difficult to remember. This script is a python powered interface to make things as easy as pressing "7". 

Please fork. Pull requests are very welcome.

Requires: Python2.x, Android Debug Bridge, Usb cable, Debian ( Ubuntu should work but must add .conf somewhere in a2createsite!), Android, Tetherbot (http://graha.ms/androidproxy/Tetherbot.apk)

Includes: One click dependency apt-get install

Works on: Debian Wheezy & Rooted Sony Xperia Ion LT28at 4G LTE


Usage: 
```
chmod+x tether-cli.py
./tether-cli.py
```

Easy to use Ncurses menu for:

    * Installing android-tools-adb
    
    * Connecting to phone via adb
    
    * Enable Port Forwarding via USB (Tetherbot)
    
    * Easy to use SSH (before was just using firefox)
    

This script was created to make it a little easier to connect to a server via SSH using the USB tethered net!

![Android Debian USB Tether in action!]( ./img/Screenshot.png
 "Android Debian USB Tether in action!")

Big thanks to http://graha.ms/androidproxy/



