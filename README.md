what to do with your odroid?


*** security first ***
add root passwd
change odroids passwd
add user and new ssh keys

*** add nfs: ***
plug you hd into usb
sh install_nfs

*** on your laptop: ***
mount odroid.ip:/mnt/usbdrive /mnt/usbdrive

continues deployment with buildbot:
sh install_buildbot

goto http://odroid.ip::8010
check docs at https://buildbot.readthedocs.io/en/v0.8.9/developer/master-slave.html
