pc-autobackup
=============

clone of https://code.google.com/p/pc-autobackup/


According to the google code page the licence is GPLv2, that's why I set the license to GPLv2 when 
I've created the repo on github.

With the application of the fix proposed by https://code.google.com/p/pc-autobackup/issues/detail?id=2


All the credit goes to the author Jeff Rebeiro (jeff@rebeiro.net) 
plus the patch by Alexander Motzkau

Thanks too both of you since I can use pc-autobackup with my Samsung NX20.


Original Description on google code page :

#Getting Started
##Requirements
- Python 2.5+ (Python 3.x not yet tested)
- Twisted

##Configuring your camera

###If your camera has already been setup with PC AutoBackup for Windows
- Mount your camera's SD card
- pc_autobackup.py --import_camera_config=/path/to/camera
- Uninstall PC AutoBackup on Windows (failure to do so will prevent this server from working)

###If you have never setup PC AutoBackup before
- Mount your camera's SD card
- pc_autobackup.py --create_camera_config=/path/to/camera

##Starting the server
- pc_autobackup.py

See pc_autobackup.py --help for more options

##Tested with the following cameras:
- DV300F
- NX1000
- WB150F
- NX20
- Does it work with your camera? Contact me and let me know!
##Tested on the following OS:
- Ubuntu 12.04 (precise) 32/64-bit
- Mac OS X 10.8.2 (Mountain Lion)

##Tested on the following Python versions:
- Python 2.7.2
- Python 2.7.3

- - -

This software is NOT created or supported by Samsung

Samsung is a registered trademark of Samsung Electronics Co., Ltd.


