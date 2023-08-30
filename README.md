# MacroPad1.0
My first macro pad design!

## Intent
This small macropad is meant to be a small prototype and proof of concept for an evolving and iterating design.

Since this will be my first experience building the supporting electronics around an ATMEGA32U4 microcontroller, 
as well as building and flashing the firmware from zero, a design with a smaller scope seemed like the best way to jump into things.

## Design Notes
1. Switches
    - This macropad will house 6 mechanical keyswitches, typical MX style and size.
2. Dimensions
    - The PCB is 76.66mm x 42.86mm (LxW) with a notch protruding for the USB connector
    - For case designers, more detailed dimensions can be found in the KiCad folder.
3. MCU
    - ATMEGA32U4-AU Microcontroller
    - This variant is actually rather large. for the next iteration thinking about going with the smaller MU variant, which comes in a QFN package, 7x7mm. This will be more challenging to solder, especially without hot air or solder paste.
4. Connection
    - Mini USB Connector
    - This is the easiest USB connector to hand solder, due to the size of the pins. great for a first prototype.
5. Current protection
    - 500mA fuse
6. Voltage protection
    - None, flyback diode would have been a good add...
