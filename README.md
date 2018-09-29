# pio-isp-blink
Sample project to write program to atmega328p via Arduino as ISP.

# Requirement

## Software

- PlatformIO

## Hardware

- Arduino Uno or Nano for Arduino as ISP
- Arduino Uno or Nano to write program via ISP
- A LED, a registor, jumper wires and a breadboard.

# Connection

atmega328p | other device
---------- | ------------
D2    | LED + Registor
D11   | ISP writer MOSI
D12   | ISP writer MISO
D13   | ISP writer SCK
Reset | ISP writer reset signal
5V    | ISP writer 5V
GND   | ISP writer GND and LED

# References
- [Arduino as ISP and Arduino Bootloaders](https://www.arduino.cc/en/Tutorial/ArduinoISP)
