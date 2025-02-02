# Additional offstes for the RDP Wrapper Library by Stas'M

### For windows 7: https://www.raymond.cc/blog/enable-remote-desktop-connection-in-windows-7-home-premium/


### For windows 10,8,.. : https://ehikioya.com/multiple-rdp-sessions-in-windows-rdp-wrapper-library/

HOW TO DO ?

Just find your windows version and accordingly add the contents given  
in .txt file to the end of file   C:\Program Files\RDP Wrapper\rdpwrap.ini file and 
make sure to add the new line at the end of the .ini file.
restart the RDPconf.exe application downloaded from library of rdpwrap.

This way enjoy now enjoy multiple RDP connections.




## Information:
This repository contains more offsets for the RDP Wrapper Library, which aren't supported natively.
As soon as a build has been added to the official repo, it will be removed here.

Just add support by adding the offsets from the text file (in this repo) corresponding to the file version "RDPConf" shows at the end of your rdpwrap.ini.

It will only contain non-Insider versions I'm able to get from the Microsoft Update Catalog or Microsoft Download Center.


## Screenshot (Windows 8.1 x64 2018-09):
![Screenshot](/RDPWrapper_Demo_w63_19093.png "Screenshot of Windows 8.1 with all updates up to 2018-09")


## Version info:
Currently this repo contains additional offsets (up to Windows 10 1803) for rdpwrap.ini with last change from 2018-10-10.

Last update: 2019-05-19

Includes versions up to 2019-04-09

If you've got a version not supported by RDP Wrapper and not posted here, feel free to open an issue with file version and download link to the msu/cab-file containing the version.

Remember, that I won't determine offsets for Insider builds or preview updates. (Builds I know, which are missing are listed in the following section)

Also remember, that I won't have enough free time to immediately determine offsets. Please be patient.

## Responsibility:
I don't take any responsibility for correctness of the offsets or potential damage caused by RDP Wrapper itself or the offsets published here.

## Missing offsets:

### Windows Vista
- 6.0.6000.20723
- 6.0.6001.22392
- 6.0.6001.22565
- 6.0.6001.22635
- 6.0.6002.22269
- 6.0.6002.22340

### Windows 7
- 6.1.7600.20661
- 6.1.7600.21085
- 6.1.7601.21855
- 6.1.7601.22477

### Windows 8
none

### Windows 8.1
none

### Windows 10 (10240)
none

### Windows 10 (10586)
none

### Windows 10 (14393)
none

### Windows 10 (15063)
none

### Windows 10 (16299)
none

### Windows 10 (17134)
none

### Windows 10 (17763)
Currently not supported by me.
