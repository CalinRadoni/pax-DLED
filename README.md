
# ESP32 controller for digital LEDs

Efficiency, hardware control for digital LEDs and Wi-Fi communications - these are just some of the caracteristics of this controller.

It is designed to control digital LEDS like:

- WS2812, WS2812B, ... (*aka* NeoPixel) and derivatives like SK6812
- APA102 (*aka* DotStar) and derivatives like SK9822

**Status:** *this is work in progress !*

## Features

- using the ESP32's RMT peripheral, the controller is able to drive two strips of digital LEDs like: WS2812, WS2812B, WS2812C, WS2812S, WS2813, WS2815, WS2812D, etc.
- using the ESP32's HSPI peripheral, the controller is able to drive a strip of digital LEDs like APA102
- two *real* logic level shifter circuits
- the power supply for LEDs is controlled using a Power MOSFET
- I2C and two general-purpose extension headers
- high efficiency synchronous buck converter
- supply voltage supervisor

## Software

My [esp32_digitalLEDs](https://github.com/CalinRadoni/esp32_digitalLEDs) repository contains code to use the ESP32's RMT peripheral to drive digital LEDs.

The code dedicated to this board is not yet built.

## Development Environment

Operating system is [Debian](https://www.debian.org/)

Tools:

- [KiCad EDA](http://kicad-pcb.org/)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Espressif IoT Development Framework](https://github.com/espressif/esp-idf)
- [Git](https://git-scm.com/)
- [GIMP](https://www.gimp.org/)
- [Inkscape](https://inkscape.org/en/)

## Versions

### Version 1

- *Fab* files are moved to the Fab-v1 directory
- The PCBs from SeeedStudio arrived
- The components are sourced
- I have built three boards
- I have developed a proof-of-concept software

### Version 0.x

Hardware revision 10 is presented in the following rendered picture:

![board-render](Docs/board-render-rev10.png)

Hardware revision 9 is presented in the following rendered picture:

![board-render](Docs/board-render-rev9.png)

Hardware revision 8 is presented in the following rendered picture:

![board-render](Docs/board-render-rev8.png)

## License

The software and documentation are released under the [GNU GPLv3](http://www.gnu.org/licenses/gpl-3.0.html) License. See the __LICENSE-GPLv3.txt__ file.

The hardware schematics are licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
See the __LICENSE-CC-BY-SA-4.0.txt__ file.
