# 5x DaemonBite SNES/NES USB Controller adapter  
# (modified version that supports 5 SNES controllers)

## Introduction
Based on the excellent work in the original project, this version will support 5 SNES gamepads at the same time.

Work around for this issue:
https://github.com/MickGyver/DaemonBite-Retro-Controllers-USB/issues/3

"The CDC Serial uses 3 endpoints. This means you can add up to 3 devices for the 32u4 and 1 for the 8/16/32u2. If you add more, some will be ignored."

I found a fix, that others have used when creating usb keyboards. It disables the CDC to free up resources. https://github.com/gdsports/usb-metamorph/tree/master/USBSerPassThruLine


## Original text and parts information:
With this simple to build  adapter you can connect NES gamepads to a PC, Raspberry PI, MiSTer FPGA etc. The Arduino Pro Micro has very low lag when configured as a USB gamepad and it is plug n' play once it has been programmed. 

## Parts
- Arduino Pro Micro (ATMega32U4)
- Male end of NES controller extension cable
- Heat shrink tube (Ø ~20mm)
- Micro USB cable

## Updated 5-port Wiring
![Assemble1](images/snes-usb-adapter-wiring%20-5player.png)

## License
This project is licensed under the GNU General Public License v3.0.
