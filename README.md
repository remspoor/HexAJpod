# HexaAJpod
Hexapod ESP8266

This repository contains

- OpenScad cad design file for a 3d printed hexapod
- stl files for printing
- hexapod firmware for the ESP8266 Arduino IDE

Have a look at: https://youtu.be/j8itndjbUWE

The hexapod will act as an Wifi Access point.
You can connect to it using the password (bestkeptsecret).
Open a web page and visit http://192.168.4.1 
This opens a page with the remote control.
When fully loaded, a websocket connection is opened.

I will upload a Bill of Material later, but you should be able to build it for less than 100$


The most important components:

1 NodeMCU - an ESP8266 development board by LoLin (v3)

2 Led / Servo drivers based on PCA9685

18 Servos by EMAX - ES08MA II, these have metal gears

5 NiMh AA Eneloop Batteries by Panasonic 

1 DC-DC converter to convert to 3.3V without the servo noise

18 M3 screws 12mm

6 Bearings 623Z

6 M3 washers

6 M3 nuts

50 2mm x 5mm screws
