## Adafruit VEML7700 Lux Sensor PCB


<a href="http://www.adafruit.com/products/5378"><img src="assets/5378.jpg?raw=true" width="500px"><br/>
Click here to purchase the right-angle STEMMA QT version from the Adafruit shop</a>
<a href="http://www.adafruit.com/products/4162"><img src="assets/4162.jpg?raw=true" width="500px"><br/>
Click here to purchase the original version from the Adafruit shop</a>

PCB files for the Adafruit VEML7700 Lux Sensor. Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/4162

### Description

Vishay has a lot of light sensors out there, and this is a nice simple lux sensor that's easy to add to any microcontoller. Most light sensors just give you a number for brighter/darker ambient lighting. The VEML7700 makes your life easier by calculating the lux, which is an SI unit for light. You'll get more consistent readings between multiple sensors because you aren't dealing with some unit-less values.

The sensor has 16-bit dynamic range for ambient light detection from 0 lux to about 120 klux with resolution down to 0.0036 lx/ct, with software-adjustable gain and integration times.

Interfacing is easy - this sensor uses plain, universal I2C. We put this sensor on a breakout board with a 3.3V regulator and logic level shifter so you can use it with 3.3V or 5V power/logic microcontrollers. [We have written libraries for Arduino (C/C++)](https://github.com/adafruit/Adafruit_VEML7700) as well as [CircuitPython (Python 3)]https://github.com/adafruit/Adafruit_CircuitPython_VEML7700) so you can use this sensor with just about any kind of device, even a Raspberry Pi!

The PID 5378 version is also one of the very few light/lux sensors we've ever seen that is right angle - that means that it senses light that is coming parallel to the PCB surface not perpendicular.

As with all Adafruit breakouts, we've done the work to make this handy light sensor super easy to use. We've put it on a breakout board with the required support circuitry and connectors to make it easy to work with. Since I2C is supported, we've added SparkFun Qwiic compatible STEMMA QT JST SH connectors that allow you to get going without needing to solder. Just use a STEMMA QT adapter cable, plug it into your favorite microcontroller or Blinka supported SBC and you're ready to rock! QT Cable is not included, but we have a variety in the shop.  

This is Kattni's first PCB design for Adafruit, it's even signed on the back!?

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Kattni Rembor for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. See license.txt for additional details.
