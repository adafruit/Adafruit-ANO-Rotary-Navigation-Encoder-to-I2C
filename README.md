## Adafruit ANO Rotary Navigation Encoder to I2C Stemma QT Adapter PCB

<a href="http://www.adafruit.com/products/5740"><img src="assets/5740.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit ANO Rotary Navigation Encoder to I2C Stemma QT Adapter. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5740

### Description

The ANO rotary encoder wheel is a funky user interface element, reminiscent of the original clicking scroll wheel interface on the first iPods. It's a nifty kit, but the pin-out is a little odd - and there's a ton of pins needed to connect to the rotary encoder and 5 button switches.

This Stemma QT breakout makes all that frustration go away - solder in the ANO Directional Navigation and Scroll Wheel Rotary Encoder (not included). The onboard microcontroller is programmed with our seesaw firmware and will track all pulses and pins for you and then save the incremental value for querying at any time over I2C. Plug it in with a Stemma QT cable for instant rotary goodness, with any kind of microcontroller from an Arduino UNO up to a Raspberry Pi to one of our QT Py's.

You can use our Arduino library to control and read data with any compatible microcontroller. We also have CircuitPython/Python code for use with computers or single-board Linux boards.

Power with 3 to 5V DC, and then use 3 or 5V logic I2C data. The INT pin can be configured to pulse low whenever rotation or push-buttoning is detected so you do not have to spam-read the I2C port to detect motion. It's also easy to add this breakout to a breadboard - with six 0.1"-spaced breakout pads - if you so choose.

Four solder jumpers can be used to change the I2C address - up to 16 can share one I2C bus! If you happen to need more, it's possible to set the I2C address with a special address-change command that is saved to the onboard non-volatile EEPROM memory.

This is just the assembled and programmed 'seesaw' PCB for the ANO encoder, the encoder is NOT included! Pick one up here. Some soldering is required to attach the encoder to the backing.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
