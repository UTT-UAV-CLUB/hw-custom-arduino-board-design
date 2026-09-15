<div align="center">

# Custom Arduino-Compatible Development Board

*Designed and documented by* [**Đỗ Bảo Đạt**](https://github.com/Datnewlevel)

[![Altium Designer](https://img.shields.io/badge/Design-Altium%20Designer-A5915F?style=flat-square)](#)
[![Base](https://img.shields.io/badge/Compatible%20with-Arduino%20Uno%20R3-00979D?style=flat-square)](#)

</div>

<br>

## Overview

A personal project to design a custom Arduino-compatible development board — a
personalized take on the Arduino Uno R3 with a few targeted improvements.

Instead of an onboard communication chip, the board uses an external USB-to-UART
module built around the **FT232RL**, keeping the board itself simpler and the
communication hardware swappable.

## Improvements Over the Arduino Uno R3

| Change | Detail |
| --- | --- |
| **Extra power pins** | Additional header rows for 5V and 3.3V, making it easier to connect peripherals and modules without daisy-chaining off the existing rails |
| **Custom layout** | Component placement and board outline redesigned for a personal touch and optimized for specific use cases |

## Design Software

Schematic and PCB layout were both designed in **Altium Designer**.

## Project Images

**Schematic**

![Schematic](Schematic.png)

**PCB Layout**

![PCB Layout](PCB.png)

**Finished Board**

![Finished Board](Circuit_board.jpg)

**USB-to-UART Communication Module**

![USB to UART Module](Module_usb_to_uart.jpg)

**Final Product**

![Product Image](Hinh_anh_san_pham.jpg)

## Board Testing

Basic peripheral tests run against the finished board to confirm functionality.

**Temperature sensor (DHT11)**

| Test 1 | Test 2 |
| --- | --- |
| ![Temperature Test 1](test_temperature_1.jpg) | ![Temperature Test 2](test_temperature_2.jpg) |

**OLED display (0.96")**

![OLED Monitor Test](test_oled_moniter.jpg)

**Ultrasonic sensor (SR04)**

![SR04 Test](test_sr04.jpg)

---

<div align="center">
<sub>Design and documentation © <a href="https://github.com/Datnewlevel">Đỗ Bảo Đạt</a>. Shared here as part of UTT UAV Club's hardware work.</sub>
</div>