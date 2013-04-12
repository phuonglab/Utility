ubuntu
======
+Fix “Could not get lock /var/lib/dpkg/lock” problem :
sudo rm /var/lib/dpkg/lock
sudo rm /var/cache/apt/archives/lock
sudo dpkg --configure -a
ps ax | grep dpkg
sudo kill
http://www.artekit.eu/stm32-usb-gamepad-interface/
vxgfdgdfg