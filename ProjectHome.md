librtmp.so.0 file for RASPBMC (Raspberry PI) - KSV Patch (Updated 15/3/2013)


IF YOU HAVE NOT INSTALLED ANY NIGHLY BUILD:

The file must replace the one existing in the following path:
/opt/xbmc-bcm/xbmc-bin/lib/xbmc/system/


IF YOU HAVE INSTALLED ANY NIGHLY BUILD:

The file must replace the one existing in the path of your update package:
./home/pi/.upgrade/(upgrade package name)/xbmc-bcm/xbmc-bin/lib/xbmc/system/

Example:
Let's supose you have installed and you are using the nightly xbmc-rbp-20130110. In this case, your librtmp file (the system is using) is located in:
./home/pi/.upgrade/xbmc-rbp-20130110/xbmc-bcm/xbmc-bin/lib/xbmc/system/


HOW TO TEST:
Test either liveflash or mips.tv rtmp streams.