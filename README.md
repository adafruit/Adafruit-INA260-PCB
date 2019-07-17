## Adafruit INA260 High or Low Side Current and Power Sensor PCB

<a href="http://www.adafruit.com/products/4226"><img src="assets/4226.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit INA260 High or Low Side Current and Power Sensor. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/4226

### Description

This breakout board may well be the last current sensing solution you every need to buy. Not only can it do the work of two multimeters, but it can do it with amazing precision and flexibility. With it you can measure high or low side DC current, the bus voltage, and have it automatically calculate the power. It can do so over impressive voltage, current, and temperature ranges with better than 1% accuracy, all while delivering the data in an easy to use format over I2C.

Works great with any microcontroller that is CircuitPython or Arduino compatible as well as single board computers such as the Raspberry Pi. It is compatible with 3V or 5V logic and can measure bus voltages up to **+36VDC. Not for use with AC voltages**.

Most current-measuring devices operate with some notable constraints that limit what they can be used for. Many are low-side only which can cause issues as the ground reference changes with current. Others like its little sister the INA219B avoid this by measuring on the high side but need to change their shunt resistor to measure different current ranges. The INA260 avoids these limitations, and with it's integrated precision shunt resistor it can be used to measure as much as **+36V** at up to **15A Continuous** on either the _high or low side_. Wow!

The voltage across the integrated 2 milliohm (.002 ohms!), 0.1% shunt resistor is measured by the internal 16 bit ADC, allowing for measurements over the impressive current range with a resolution of 1.5 mA. (The resistance of the resistor is so low that some multimeters will register it as a short!)

In a high side configuration the bus voltage measurement and power calculation can be retrieved accurately, however advanced hackers wanting to measure bus voltage in a low side configuration will need to cut the jumper connecting **V+** to **VBUS** and connect the **VBUS** pin to the voltage bus.

Comes as a fully assembled breakout board with a 5.08mm terminal block (extra chunky!) and header. Some light soldering is required to attach the header and terminal block.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Bryan Siepert for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
