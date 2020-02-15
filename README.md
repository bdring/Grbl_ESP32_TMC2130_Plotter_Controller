## TMC2130 Pen / Laser Controller

![](https://github.com/bdring/Grbl_ESP32_TMC2130_Plotter_Controller/blob/master/V2/docs/PCB_V2.jpg)

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

The firmware used is Grbl_ESP32. There is a special branch that supports the TMC2130.

### Open Source

- [Schematic](https://github.com/bdring/Grbl_ESP32_TMC2130_Plotter_Controller/blob/master/V2/docs/schematic_v2.pdf)
- [Gerber Files](https://github.com/bdring/Grbl_ESP32_TMC2130_Plotter_Controller/tree/master/gerbers)
- [BOM](https://github.com/bdring/Grbl_ESP32_TMC2130_Plotter_Controller/blob/master/docs/BOM.csv)
- [Source files (DipTrace)](https://github.com/bdring/Grbl_ESP32_TMC2130_Plotter_Controller/tree/master/source)

### Version History

- V2
   - Moved X Limit Switch form GPIO 2 to 32. Works better on dev boards that have an LED on that pin.
   - The footprint for the stepper drivers no include the diag pins
   - Added jumpers to optional connect diag pins to limit pins
   - Grounded TMC2130 N/C pin to make it compatible with TMC5160 drivers. The capacitor size is probably not ideal for use with the full capacity of the TMC5160, but should work.
   - Added 5V output (fan connector)



### Getting Started

- [Wiki for this design](https://github.com/bdring/Grbl_ESP32_TMC2130_Plotter_Controller/wiki)
- [Wiki for Grbl_ESP32](https://github.com/bdring/Grbl_Esp32/wiki)
- Getting one. I have a few extra, just ask for one via [this Issue.](https://github.com/bdring/Grbl_ESP32_TMC2130_Plotter_Controller/issues/1) 
