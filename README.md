# adb-tether

Requires adb, tetherbot.apk, and I like to use proxychains with it. Python + curses interface to turn difficult-to-remember commands into one letter commands.

This script makes using Tetherbot easier. Tetherbot shares internet from android to debian via usb, but requres some command lines that are difficult to remember. This script is a python powered interface to make things as easy as pressing "7". 

Thank you

Please fork. Pull requests are very welcome.

Requires: Python2.x, Android Debug Bridge, Usb cable, Debian ( Ubuntu should work ), Android, Tetherbot (http://graha.ms/androidproxy/Tetherbot.apk)

Includes: One click dependency apt-get install

Works on: Debian Wheezy & Rooted Sony Xperia Ion LT28at


Usage: 
```
chmod+x adb-tether
./adb-tether
```

Install: 
```
chmod+x adb-tether
sudo cp adb-tether /usr/local/bin/
```



##Easy to use Ncurses menu for:

    * Installing android-tools-adb
    
    * Connecting to phone via adb
    
    * Enable Port Forwarding via USB (Tetherbot)
    
    * Easy to use SSH (before was just using firefox)

    * Near future: more adb functions (screen shot, backup phone, database sqlite3 commands, and better scp function)
    

This script was created to make it a little easier to connect to a server via SSH using the USB tethered net!

![Android Debian USB Tether in action!]( ./img/Screenshot.png
 "Android Debian USB Tether in action!")

Big thanks to http://graha.ms/androidproxy/

#ADB-TETHER LICENSE
```
android-tether is released under the MIT License!
You may "use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software" as long as your also publish this LICENSE file with it!

Thanks for using Free Libre Open Source Software!

                 _   _     
  __ _  ___ _ __| |_| |__  
 / _` |/ _ \ '__| __| '_ \ 
| (_| |  __/ |  | |_| | | |
 \__,_|\___|_|   \__|_| |_|
                           

The MIT License (MIT)

Copyright (c) 2015 aerth@isupon.us

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

```


#TETHERBOT LICENSE
```
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE. 
```

