# CH32V003J4M6-Dev-Board
Basic CH32V003J4M6 Dev Board

CH32V003J4M6 Dev Board designed for easy prototyping and reliable use.
It breaks out all MCU pins for maximum flexibility, while keeping a clean and minimal footprint.

An onboard debug / status **LED on PC4** can be enabled or completely disconnected via a solder jumper, giving you full control over pin usage.
Programming is straightforward thanks to the dedicated 3-pin SWIO header, making it fully compatible with standard WCH debugging tools.

Also includes a TVS diode for input protection, and convenient power is provided through a 6-pin USB-C connector, ensuring easy integration into modern setups.
Ideal for breadboard experimentation, small projects, or as a compact development platform for the CH32V003 series.

<img width="379" height="300" alt="top" src="https://github.com/user-attachments/assets/f85a6711-8901-43cf-a667-86d5aaaffef6" /> <img width="352" height="300" alt="back" src="https://github.com/user-attachments/assets/36252a41-1364-4047-87d5-217d2d3f52c4" />



## Programming

**To program this board, you will need a WCH-LinkE programmer. Be sure you buy the correct one (with the letter "E" at the end)**

The board can be programmed via MountRiver Studio or via the Arduino IDE using the official WCH core:
(https://github.com/openwch/ch32v003)

You will also have to install the drivers that can be found here https://github.com/openwch/ch32v003/tree/main/WCH-LinkUtility/Drv_Link

**Also don't forget, before connecting the programmer to your PC, make sure to press the MODE_S button on the WCH-LinkE to switch it into the correct mode (the one where the blue LED is off).**

Have fun !
