## TMC2130 Pen / Laser Controller

![](http://www.buildlog.net/blog/wp-content/uploads/2019/05/tmc2130_plot1.jpg)

This is a simple controller for a Pen Plotter that uses Grbl_ESP32 as the firmware and TMC2130 stepper motor drivers in SPI mode. There is a hobby servo connector for pen up/down control. The PWM signal (3.3V TTL) on that could also be used to control a laser module.

### Features

- ESP32 Controller Socket
- SD Card Socket (under ESP32)
- (2) TMC2130 Stepper Driver Sockets (SPI Mode). Note: Non SPI drivers will not work.
- (2) Limit switch connectors
- Hobby Servo connector
- Strong 5V 3A power supply
- All the freaking awesome features of Grbl_ESP32

### Firmware

The firmware used is Grbl_ESP32. There is a special branch that supports the 

### Open Source

- [Schematic](https://github.com/bdring/Grbl_ESP32_TMC2130_Plotter_Controller/blob/master/docs/schematic_v1.pdf)
- [Gerber Files](https://github.com/bdring/Grbl_ESP32_TMC2130_Plotter_Controller/tree/master/gerbers)
- [BOM](https://github.com/bdring/Grbl_ESP32_TMC2130_Plotter_Controller/blob/master/docs/BOM.csv)
- [Source files (DipTrace)](https://github.com/bdring/Grbl_ESP32_TMC2130_Plotter_Controller/tree/master/source)

### Getting Started

- [Wiki for this design](https://github.com/bdring/Grbl_ESP32_TMC2130_Plotter_Controller/wiki)
- [Wiki for Grbl_ESP32](https://github.com/bdring/Grbl_Esp32/wiki)
- Getting one. I have a few extra, just ask for one via [this Issue.](https://github.com/bdring/Grbl_ESP32_TMC2130_Plotter_Controller/issues/1) 
