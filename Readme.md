# Irdroid-Rpi Infrared Transceiver for Raspberry Pi

The latest gadget that we are working on is the Irdroid-Rpi Infrared Transceiver HAT / Add-on board for Raspberry Pi. The board provides Infrared Transmitter , Infrared Receiver and UEXT interconnect for Olimex sensors and boards designed with the UEXT connector. The board can be stacked on top of the Rpi board and you could turn your Rpi into a fully functional Infrared remote control for you home infrared consumer electronics. The Irdroid-Rpi is compatible with the LIRC/ Lirc GPIO driver for raspberry Pi and the LIRC utilities for recording and transmitting infrared signals can be used. The Irdroid-Rpi uses a optical IR amplification technique that allows to transmit high power IR signal by signal amplification after the IR light is emitted.

- Infrared Transceiver add-on / HAT for Raspberry Pi
- Infrared Transmitter @940nm with 10+ meters range
- Infrared Receiver up to 40khz and 10+ meters of receive range
- On-board UEXT Interconnect for connecting Olimex sensors and boards.
- Open Source Hardware.

### Version
1.0

### Installation Instructions

Detailed Installation Instructions https://irdroid.eu/wp-content/uploads/2020/03/Irdroid-Rpi-Installation-Guide.txt

### Grab a sample

You can grab a sample board from http://www.irdroid.eu/irdroid-rpi-infrared-transceiver-raspberry-pi/
### Tech

The Irdroid-Rpi infrared transceiver for Raspberry Pi is also designed with the possibility to connect sensors and boards from Olimex (http://www.olimex.com) by using the on-board UEXT connector, designed by Olimex. You can check here what sensors are supported https://www.olimex.com/Products/Components/Sensors/ .

### Todos

 - Add holders for the infrared leds in schematic
 
### Updates

Irdroid-Rpi now has a DT Overlay support via the on-board eeprom that now ships with every board. Once attached to a Raspberry Pi, the Irdroid-Rpi Hat will be recognized automatically, it will set the board inputs and outputs, and it will load the appropriate Kernel LIRC-RPI drivers. This feature improoves user experience and it provides plug-n-play support for the Product. The user will only have to install lircd (if not shipped by default with the distribution used).

The Irdroid-Rpi board details such as Vendor and Product IDs are available in 

/proc/device-tree/hat

To query Product & Vendor use:

$ more product  

$ more vendor

License
----
GPL 2.0

