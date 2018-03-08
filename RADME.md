# ESP_NPXL breakout board
This is a breakout board for the ESP-12E (ESP8266 chip).

It is specifically designed to drive neopixel (WS2812) strips. It supports a 5V Powersupply connected to a
barrel jack, and uses this voltage to drive the neopixels directly. 3.3V for the ESP-12E chip 
is derived by a voltage regulator. The 3.3V logic signals for talking to the neopixels are
translated to 5V signals with a 74HCT125T14 level shifter and are exposed with seperate headers to connect neopixels 
directly.

# BOM
[Here](https://docs.google.com/spreadsheets/d/1_CaYb2ciAQcWB66eh2JpWhilTOlse78BdJ35IBW88Fk/edit?usp=sharing) is a 
partslist with links to shops where I bought the parts. Unfortunately one of them is no longer existing. If
you have a proposition let me know...

# Contributing
Feel free contributing or doing whatever with this design. As board design is only a hobby of mine it's probably 
not a good design anyway ;)
