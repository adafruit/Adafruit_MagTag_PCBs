## Adafruit MagTag PCB

<a href="http://www.adafruit.com/products/4800"><img src="assets/4800.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit MagTag.

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/4800

### Description

The Adafruit MagTag combines the new ESP32-S2 wireless module and a 2.9" grayscale E-Ink display to make a low-power IoT display that can show data on its screen even when power is removed! The ESP32-S2 is great because it builds on the years of code and support for the ESP32 and also adds native USB support so you can use this board with Arduino or CircuitPython!

We designed this board to be low-power friendly - with a spot for a 350 or 420 mAh battery and built in battery charging over USB C. During deep sleep, with the NeoPixels and speaker amplifier disabled, we measured 250uA power draw so you can run for a few weeks between charges.

And of course, the Mag in MagTag stands for magnetic. We have four M3 standoffs that will work perfectly with these mini magnet feet. (Originally they're designed for RGB Matrices but they'll do an excellent job here as well). Screw on the feet and you can attach this display to a metallic shelf, fridge, or bench.

Here's the cool hardware we put together:

* ESP32-S2 240MHz Tensilica processor - the next generation of ESP32, now with native USB so it can act like a keyboard/mouse, MIDI device, disk drive, etc!
* WROVER module has FCC/CE certification and comes with 4 MByte of Flash and 2 MByte of PSRAM - you can have huge data buffers
* 2.9" grayscale display with 296x128 pixels. Each pixel can be white, light gray, dark gray or black. Compared to 'tri-color' displays with a red pigment, this display takes a lot less time to update, only about a second instead of 15 seconds!
* USB C power and data connector
* Four RGB side-emitting NeoPixels so you can light up the display with any color or pattern
* Four buttons can be used to wake up the ESP32 from deep-sleep, or select different modes
* Triple-axis accelerometer (LIS3DH) can be used to detect orientation of the display
* Speaker/Buzzer with mini class D amplifier on DAC output A0 can play tones or lo-fi audio clips.
* Front facing light sensor
* STEMMA QT port for attaching all sorts of I2C devices
* Two STEMMA 3 pin JST connectors for attaching NeoPixels, speakers, servos or relays.
* On/Off switch
* Boot and Reset buttons for re-programming

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution.
See license.txt for additional details.
