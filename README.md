LapsePiTouch
============

Touchscreen Timelapse controller for Raspberry Pi and Adafruit PiTFT by [David Hunt](http://www.davidhunt.ie) 

Based on code by PaintYourDragon (Phil B) for Adafruit Industries

Read more about this project at [Dave's Blog](http://www.davidhunt.ie/?p=3349)

Enjoy!

Modification for HiRes Display (480x320) and use gphoto2 for camera triggering

![LapsePi Touch](http://i.imgur.com/6lUPMah.png?1)

**Prerequisites:**

You must have gone through the [Adafruit PiTFT setup instructions](https://learn.adafruit.com/adafruit-pitft-3-dot-5-touch-screen-for-raspberry-pi).

You must have gone through the [WiringPi-Python Setup instructions](https://github.com/WiringPi/WiringPi-Python).

You must have to install gphoto2 by the following command:
	
	sudo apt-get install gphoto2

**Get repo:**
    
    git clone https://github.com/koehleru/LapsePiTouch.git
    
    
**Usage:**

    cd LapsePiTouch

    sudo python lapse_hi.py
	
Once youve got that working, have the Pi boot straight into the time-lapse software by editing /home/pi/.config/lxsession/LXDE-pi/autostart file:

	@lxterminal -e /home/pi/lapsepiplauncher.sh

And create the script /home/pi/lapsepiplauncher.sh by adding the the following lines:

	#!/bin/sh
	cd LapsePiTouch
	sudo python lapse_hi.py

Full details at: [Dave's Blog](http://www.davidhunt.ie/?p=3349)
