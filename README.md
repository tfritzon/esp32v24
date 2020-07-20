# esp32v24
ESP32-based V.24 plug

ESP32V24 is an ESP32 with a RS-232, or V.24, interface that fits into a 9-pin D-Sub
backshell. The idea with it is to be able to comfortably use a device equiped with
only a serial port over a network. Possible uses are as a terminal server for a
retro computer, a network CAT interface for a ham radio or to interface with an
old PLL that only has serial interfaces.

So far, this is a project in it's infancy, but possible features might be:

* Application framework that includes:
  * Connecting to a Wifi network
  * Webserver for configuration
  * RESTful service for runtime control
  * Error handling
  * Zeroconf with configurable name, to be addressable as _name_.local
* OTA updates
* Application API to make it simple to develop a domain specific application.
* AT command parser to be used from within the connected device

