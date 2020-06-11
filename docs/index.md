# Welcome

Welcome to the DCC++ EX Web page. DCC++ EX is an open-source hardware and software platform for the operation of DCC-equipped model railroads. It is based on Gregg E. Berman's Arduino based DCC++ software. DCC-EX picks up where the original DCC++ left off by addressing some previous issues in order to be able to release what we now call "DCC++ Classic" - Everything you enjoyed in the original version in a stable release. In addition, we have have continued development with an all new version called "DCC-EX" that includes enhancements and upgrades. We intend to organize this all in one place so that development can continue and the platform can adjust to new hardware and technnology.

# Our Mission

Our mission is to supply the model railroading community with an Arduino (and optional accessories) based open source alternative to commercial DCC systems; One that is simple, affordable, expandable, and allows for a fast and successful out of box experience to control model trains and accessories. Further, it is our goal that this project be organized, documented, and maintained so that it can continue into the future without fear that it will be abandoned.

# What is DCC++ EX?

In addition to controlling your trains, DCC++ also includes advanced features such as dedicated logic for operating turnouts, and the ability to create and control your own digital inputs, digital outputs, and even analog inputs --- great for reading panel switches, sensors, and occupancy detectors, as well as controlling servos, LEDS, and anything else you can imagine! Basically, DCC-EX can control anything using a DCC signal over two tracks, two wires, or via wired Ethernet or WiFi.

DCC++ supports the full set of [NMRA Digital Command and Control (DCC) standards](http://www.nmra.org/dcc-working-group "NMRA DCC Working Group"), including:

* simultaneous control of multiple locomotives
* 2-byte and 4-byte locomotive addressing
* 128-step speed throttling
* Activate/de-activate all accessory function addresses 0-2048
* Control of all cab functions F0-F28
* Main Track: Write configuration variable bytes and set/clear specific configuration variable (CV) bits
* Programming Track: Same as the main track with the addition of reading configuration variable bytes

# What's new since DCC++ Classic?

* Direct support for all the most popular motor control boards
* I2C Display support
* Improved short circuit detection and automatic reset from an overload
* Current reading, sensing and ACK detection settings in milliAmps instead of just pin readings
* Improved adherence to the NMRA DCC specification
* New Communication Manager to handle input and output to multiple sources simultaneously (JMRI, Cab controllers, etc.)
* Arduino Network Shield and ESP8266 WiFi support
* Railcom Cutout (Beta)
* The code is now simpler, modular, faster and provides an API Library for developers and easy expansion
* No more jumpers! (Beta)

### The system consists of multiple parts:

* __Base Station__ - An Arduino, motorboard and the DCC-EX uploadable firmware
* __Controller__ - The JMRI Train Controlling and Decoder Programming Software
* __Track Power Supply__ - A DC power supply to provide power to the rails
* __Computer__ - You supply a laptop or other computer to run JMRI and connect via a USB cable to the Arduino
* __DCC++ EX Software__ - The DCC++ EX sofware (called a "sketch") loaded onto the Arduino

There are many flavors and options to choose from. The DCC-EX system is incredibly expandable and adaptable. However, to keep it simple we will be covering a "Starter System" and providing you with a Quick Start guide to get you going. There is a more detailed User Manual for those who want to dig deeper and explore other options. The manual covers other motor control boards, other controllers, wireless communication options, current sensing options, using a Raspberry Pi instead of a laptop, and more. You aren't limited to just one or two choices and we've got you covered if you want to put together the perfect system for you.

Next Page: [Starter Kit](starter-kit.md)
