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

Role         | atmega328p | other device
------------ | ---------- | ------------
LED control  | D2         | LED + Registor
MOSI         | D11        | D11 of Arduino as ISP
MISO         | D12        | D12 of Arduino as ISP
SCK          | D13        | D13 of Arduino as ISP
Reset signal | Reset      | D10 of Arduino as ISP
5V           | 5V         | 5V of Arduino as ISP
GND          | GND        | GND of LED and Arduino as ISP

# Command

```
pio run -t program
```

# References
- [Arduino as ISP and Arduino Bootloaders](https://www.arduino.cc/en/Tutorial/ArduinoISP)
