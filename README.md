**Archphile Web Radios pls files**

This repository includes all web radios found in Archphile images.

The base of this were are Moodeaudio Webradios found in [this link](http://moodeaudio.org/#download). The purpose of this repo is to further modify the list with additions/removals.

In order to always have the latest webradios you can use the following procedure which replaces the existing pls files in Archphile images

	wget https://raw.githubusercontent.com/archphile/AthensFMRadios/master/archphile-script/wrf.sh
	chmod +x wrf.sh
	./wrf.sh
	

**NOTE:** 0.99.73 is missing unzip which is required by wrf script. In order to install unzip, edit mirrorlist:

	nano /etc/pacman.d/mirrorlist
	
enable the first server line, save and then install unzip command:

	pacman -Sy unzip
	
Now you are ready to follow the initial procedure.