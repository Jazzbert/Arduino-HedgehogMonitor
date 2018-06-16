# Arduino Hedgehog Monitor
This is a simple monitor that currently provides temperature and humidity display information on an OLED display.  This was created to monitor cage temperature for our hedgehog, Cybil.  Currently consider this licensed under MIT license for public use unless other licenses should aply.
## What It Does
### Environment Monioring
This monitor displays current temperature and humidity as read from a DHT22 Temparature and Humidity Sensor.  It keeps track of high and low temperatures since last boot and displays on-screen as well.  Shutting down or resetting the unit will reset the maximum and minimum temperatures.

## Parts Used
* Adafruit Feather HUZZAH with ESP8266 WiFi w/ Stacking Headers _Adafruit Product ID: 3213_
* Adafruit FeatehrWing OLED - 128x32 OLED Add-on _Adafruit Product ID: 2900_
* DHT 22 Temparature-Humidy Sensor _Adafruit Product ID: 385_
* 16k &Omega; resistor
* 28 AWG Jumper Wires (prototype) / 22 AWG Wire (final)
* Half-size breadboard (prototype) / PCB prototype board (final)

## TODOs
* **Complete** ~~Clean up README, licensing, and similar documentation~~
* **Active:** Enable AC relay for switching on/off heat lamp
* Enable wifi capability for
  * Web history tracking
  * Phone alerts for over/under temp
  * Phone alerts for system errors (e.g., offline)
* Water level detection?
* Food level detection?
* Activity monitor/tracker (e.g., revolutions per minute & total revolutions per day on wheel)
* Video capture for super-cute moments

![Cybil the Hedgehog!](./cybil.jpg "Cybil the Hedgehog!")
