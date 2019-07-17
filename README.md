## Adafruit PyBadge PCB

<a href="http://www.adafruit.com/products/4200"><img src="assets/4200.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit PyBadge. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/4200

### Description

What's the size of a credit card and can run CircuitPython, MakeCode Arcade or Arduino? That's right, its the **Adafruit PyBadge!** We wanted to see how much we could cram into a ​3 3⁄8 × ​2 1⁄8 inch rounded rectangle, to make an all-in-one dev board with a lot of possibilities, and this is what we came up with.

The PyBadge is a compact board, like we said, it's credit card sized. It's powered by our favorite chip, the ATSAMD51, with 512KB of flash and 192KB of RAM. We add 2 MB of QSPI flash for file storage, handy for images, fonts, sounds, or game assets.

On the front you get a 1.8" 160x128 color TFT display with dimmable backlight - we have fast DMA support for drawing so updates are incredibly fast. There's also 8 silicone-top buttons, they are clicky but have a soft button top so they're nice and grippy. The buttons are arranged to mimic a gaming handheld, with a d-pad, 2 menu-select buttons and 2 fire-action buttons. There's also 5 NeoPixel LEDs to dazzle or track activity.

On the back we have a full Feather-compatible header socket set, so you can plug in any FeatherWing to expand the capabilities of the PyBadge. There's also 3 STEMMA connectors - two 3-pin with ADC/PWM capability and one 4-pin that connects to I2C - you can use this for Grove sensors as well.

For built in sensors, there's a light sensor that points out the front, and a 3-axis accelerometer that can detect taps and free-fall. To make bleeps and bloops, there's a built in buzzer-speaker. [For projects where you need more volume, you can plug in one of our 8 ohm speakers](https://www.adafruit.com/product/3923).

[You can power the PyBadge from any of our LiPoly batteries, but we like this 400mAh one](https://www.adafruit.com/product/3898.) An on-off switch will save battery power when not in use. Or power from the Micro USB port - it will also charge up the battery if one is attached.

Now, how to program it? Well you've got a lot of options!

[MakeCode Arcade is the easiest to start for making games](https://arcade.makecode.com/), you can drag-and-drop blocks and load games over the disk-drive bootloader
[CircuitPython](https://circuitpython.org/board/pybadge/) lets you draw graphics, play wave files and print out text in any fonts - all in Python! There's tons of sensor support as well.
Arduino is low level, powerful, but a little more challenging. [You can use Adafruit Arcada](https://github.com/adafruit/Adafruit_Arcada) to interface with the hardware and it will abstract some of the nitty-gritty details like reading buttons for you.
Here's a list of everything you get

 * **ATSAMD51J19** @ 120MHz with 3.3V logic/power - 512KB of FLASH + 192KB of RAM
 * **2 MB of SPI Flash** for storing images, sounds, animations, whatever!
 * **1.8" 160x128 Color TFT Display** connected to its own SPI port
 * **8 x Game/Control Buttons** with nice silicone button tops (these feel great)
 * **5 x NeoPixels** for badge dazzle, or game score-keeping
 * **Triple-axis accelerometer** (motion sensor)
 * **Light sensor**, reverse-mount so that it points out the front
 * **Built in buzzer mini-speaker**
 * **Mono Class-D speaker driver for** 4-8 ohm speakers, up to 2 Watts
 * LiPoly battery port with built in recharging capability
 * USB port for battery charging, programming and debugging
 * Two female header strips with Feather-compatible pinout so you can plug any FeatherWings in
 * JST ports for NeoPixels, sensor input, and I2C (you can fit I2C Grove connectors in here)
 * Reset button
 * On-Off switch

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
