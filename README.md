# WTF is this

I wasn't satisfied with the existing toolhead boards on the market so I made
my own...

NOTE: Not tested yet

* 24V/data connection on 2x2p Micro-Fit 3.0 connector. Configured for CAN bus
  by default, but USB may be selected with solder jumpers.
* STM32G0B1 microcontroller
* Heater output on Micro-Fit 3.0 connector
* 2 thermistor ports
* 2 MOSFETs for fans, both 5V/24V selectable with solder jumpers
  * Part cooling fan output has 2 connectors in parallel
  * Hotend fan port has a sensor pin for a tachometer
* TMC2209 stepper driver
* Neopixel port
* 3 endstop ports + 1 probe port
* SPI bus exposed on 6-pin JSTSH connector (for e.g. an external
  accelerometer)

## Copyright

Copyright Adrian Keet 2024.

This source describes Open Hardware and is licensed under the CERN-OHL-S v2.

You may redistribute and modify this source and make products using it under
the terms of the CERN-OHL-S v2 (https://ohwr.org/cern_ohl_s_v2.txt).

This source is distributed WITHOUT ANY EXPRESS OR IMPLIED WARRANTY, INCLUDING
OF MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A PARTICULAR PURPOSE.
Please see the CERN-OHL-S v2 for applicable conditions.

Source location: https://github.com/arkeet/utb36-toolhead-board

As per CERN-OHL-S v2 section 4, should You produce hardware based on this
source, You must where practicable maintain the Source Location visible on the
packaging and documentation of this product or other products you make using
this source.
