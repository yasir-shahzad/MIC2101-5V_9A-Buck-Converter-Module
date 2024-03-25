# DC to DC Buck Converter [Adjustable, Efficient,5V 9A]
Introducing our DC-DC Buck Converter: Adjustable, Efficient, delivering 5V at 9A! Empower your projects with precision and power efficiency.

![CH32V003A4M6_DevBoard_pic1.jpg](https://github.com/yasir-shahzad/MIC2101-5V_9A-Buck-Converter-Module/blob/master/images/0J5585.1200.jpg)

# Pinout
![CH32V003A4M6_DevBoard_pinout.png](https://github.com/yasir-shahzad/MIC2101-5V_9A-Buck-Converter-Module/blob/master/images/0J5587.400.jpg)

# Buck Converter Overview
## Overview
Buck converters are a workhorse in the world of electronics, efficiently stepping down a higher voltage DC input to a lower voltage DC output. Whether you're powering a microcontroller project or building a custom LED driver, a buck converter offers a compact and versatile solution. In this article, we'll guide you through the process of designing and building your own buck converter.

## Schematic Diagram
![CH32V003_block.png](https://github.com/yasir-shahzad/MIC2101-5V_9A-Buck-Converter-Module/blob/master/images/Schematic.png)

## Features

- **Input Voltage**: 5 to 38 V (See below for regulator's dropout voltage details)
- **Output Voltage**: Fixed 5 V (±4% accuracy); adjustable with external resistor
- **Output Current**: Typically 4 A to 8 A continuous
- **Protection Features**:
  - Integrated reverse-voltage protection
  - Over-current and short-circuit protection
  - Over-temperature shutoff
  - Soft-start
  - Under-voltage lockout
- **Efficiency**: Typically 80% to 95%, varying with input voltage and load
- **Switching Frequency**: Automatically adjusted at light loads for high efficiency
- **Quiescent Current**: 800 µA typical no-load; adjustable down to 10 µA/V on VIN
- **Power Good Output**: Indicates inability to maintain set output voltage
- **Compact Size**: 1.6" × 0.8" × 0.3" (40.6 × 20.3 × 7.6 mm)
- **Mounting**: Four 0.086" holes for #2 or M2 screws
- **Connectivity Options**: Smaller holes for 0.1" header pins; larger holes for terminal blocks


# References, Links and Notes
- [EasyEDA Design Files](https://oshwlab.com/wagiminator)
- [MCU Templates](https://github.com/wagiminator/MCU-Templates)
- [MCU Flash Tools](https://github.com/wagiminator/MCU-Flash-Tools)
- [MounRiver Studio](http://www.mounriver.com/)
- [ch32003fun SDK](https://github.com/cnlohr/ch32v003fun)
- [arduino_core_ch32](https://github.com/openwch/arduino_core_ch32)
- [arduino-wch32v003](https://github.com/AlexanderMandera/arduino-wch32v003)
- [CH32V003 with PlatformIO](https://github.com/Community-PIO-CH32V/platform-ch32v)
- [CH32V003 on openwch](https://github.com/openwch/ch32v003)
- [MuseLab nanoCH32V003](https://github.com/wuxx/nanoCH32V003)
- [CH32V003 datasheets](http://www.wch-ic.com/products/CH32V003.html)
- [WCH-Link user manual](http://www.wch-ic.com/downloads/WCH-LinkUserManual_PDF.html)
- [WCH Official Store on AliExpress](https://wchofficialstore.aliexpress.com)

![CH32V003A4M6_DevBoard_pic2.jpg](https://raw.githubusercontent.com/wagiminator/Development-Boards/main/CH32V003A4M6_DevBoard/documentation/CH32V003A4M6_DevBoard_pic2.jpg)
![CH32V003A4M6_DevBoard_pic3.jpg](https://raw.githubusercontent.com/wagiminator/Development-Boards/main/CH32V003A4M6_DevBoard/documentation/CH32V003A4M6_DevBoard_pic3.jpg)

# License

![license.png](https://www.gnu.org/graphics/gplv3-88x31.png)

This work is licensed under the GNU General Public License v3.0.

