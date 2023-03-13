(See bottom of this file for DerfTastic's additions)

# bitluni's ESP32 VGA
A simple VGA output with 14Bit color and external DACs over parallel I²S

Thanks for any support!

Patreon (https://patreon.com/bitluni)
Paypal (https://paypal.me/bitluni)

Version 0.1

#License
bitluni 2019
Creative Commons Attribution ShareAlike 2.0
https://creativecommons.org/licenses/by-sa/2.0/

If you need another license, please feel free to contact me

# DerfTastic's Additions (so far)

- Got the project to work on my ESP-WROOM-32S development board with the [PlatfromIO](https://platformio.org/) extension for VSCode.
- Got one of my own models of a table in the `gfx/` folder to work

This was my first time actually using an ESP32 so I was really surprise at how fast it actually is. I'll probably be using this more than my arduino for quick microcontroller things now.

![Picture of ESP32-controlled monitor with a 3D model of a thinking man](images/2023-03-13-032257.jpg)
![Picture of the breadboard setup with the ESP32 dev board and a DAC controlling one color channel](images/2023-03-13-032403.jpg)

### Future plans:

- Allow button input to be taken in so that a game can actually be made
- Make an interface to draw 2D sprites