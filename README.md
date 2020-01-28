# DaemonBite-CD32-USB
## Introduction
With this simple to build  adapter you can connect Amiga CD32 gamepads and Commodore/Amiga/Atari joysticks to a PC, Raspberry PI, MiSTer FPGA etc. The Arduino Pro Micro has very low lag when configured as a  USB gamepad and it is plug n' play once it has been programmed. 

## Parts you need
- Arduino Pro Micro (ATMega32U4)
- Male end of Mega Drive controller extension (or DSUB 9Pin Male connector and some wires)
- SPDT Switch (2.54mm/0.1" pitch)
- Heat shrink tube (Ø ~20mm)
- Micro USB cable

## Wiring
![Assemble1](images/sega-usb-adapter-wiring.png)

## How to assemble
![Assemble1](images/sega-usb-adapter-1.png)
![Assemble1](images/sega-usb-adapter-2.png)  
(The switch goes to pins GND-GND-2 even if the picture above shows it connected to GND-2-3)
![Assemble1](images/sega-usb-adapter-3.png)
![Assemble1](images/sega-usb-adapter-4.png)

## The Switch
When the switch is in the position closer to the USB port of the Arduino Pro Micro, the adapter will be in Commodore/Amiga/Atari two-button mode. When it is in the other position, it will be in CD32 mode.

## License
This project is licensed under the GNU General Public License v3.0.
