## Modified by SwitchDoc Labs to Support the Thunder Board
## November 2017
## Version 1.1




This script will only work if the correct kernel modules are loaded
on your Pi.  Adafruit has a nice [tutorial](http://learn.adafruit.com/adafruits-raspberry-pi-lesson-4-gpio-setup/configuring-i2c)
set up,
 
You will likely not see anything show up when you run `i2cdetect`.  Test using demo.py

## Installation

You can copy the files into your main program directory (suggested)

import: <BR>
from SDL_Pi_Thunderboard_AS3935 import  AS3935


RaspberryPi-AS3935
==================

Original Source:

[![Build Status](https://travis-ci.org/pcfens/RaspberryPi-AS3935.png?branch=master)](https://travis-ci.org/pcfens/RaspberryPi-AS3935)

A python library and demo script for interacting with the
[AMS Franklin Lightning Sensor](http://www.ams.com/eng/Products/RF-Products/Lightning-Sensor/AS3935).

