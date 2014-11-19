LapsePiTouch
============

Touchscreen Timelapse controller for Raspberry Pi and Adafruit PiTFT by [David Hunt](http://www.davidhunt.ie) 

Based on code by PaintYourDragon (Phil B) for Adafruit Industries

Read more about this project at [Dave's Blog](http://www.davidhunt.ie/?p=3349)

Enjoy!

Modification for HiRes Display (480x320) and use gphoto2 for camera triggering

![LapsePi Touch](http://i.imgur.com/0LiKRwd.jpg)

**Prerequisites:**

You must have gone through the [Adafruit PiTFT setup instructions](https://learn.adafruit.com/adafruit-pitft-3-dot-5-touch-screen-for-raspberry-pi).

You must have gone through the [WiringPi-Python Setup instructions](https://github.com/WiringPi/WiringPi-Python).

**Get repo:**
    
    git clone https://github.com/koehleru/LapsePiTouch.git
    
    
**Usage:**

    cd LapsePiTouch

    sudo python lapse_hi.py
	
Once youve got that working, have the Pi boot straight into the time-lapse software by editing /etc/rc.local and adding the following lines before exit 0

	cd /home/pi/LapsePiTouch

	python lapse_hi.py


Full details at: [Dave's Blog](http://www.davidhunt.ie/?p=3349)

for donation 1LPGEoSdDaXrNuhuWtEH1EyFoTM7gjYs5h
