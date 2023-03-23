# ESP32 LED Matrix Controller with WLED

This is a project to build a LED matrix controller using an ESP32 microcontroller and the WLED software. The aim is to create a gift prototype that can drive an LED matrix and possibly a small screen.

## Overview

The ESP32 microcontroller will be used to drive a 25 WS2812B LED matrix. The WS2812B LEDs will be mounted on the same PCB as the ESP32. A TPD4E02B04 will be used to protect the board from voltage spikes. An AMS1117 3.3V voltage regulator will convert the 5V power from the USB C port to 3.3V power for the ESP32. The CH340 USB to serial converter will be used for programming the ESP32 and for USB connectivity.

## Circuit Diagram

The diagram was created using KiCad.

![Circuit Diagram](https://raw.githubusercontent.com/Coniass/ESP32-WS2812B-Matrix/main/Schematic.jpg)

## Programming the ESP32

To program the ESP32, you will need the Arduino IDE and the ESP32 board files installed. Follow the instructions on the [ESP32 Arduino Core GitHub page](https://github.com/espressif/arduino-esp32) to install the board files.

To upload the code to the ESP32, connect it to your computer using a USB cable. In the Arduino IDE, select the appropriate board and serial port, and then upload the code.

## Installing WLED

You can install the WLED software on the ESP32 by following the instructions on the [WLED install page](https://install.wled.me/).

## Contributing

I welcome criticism and suggestions for improvement. If you have any suggestions or improvements, please open an issue or a pull request.
