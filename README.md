# NanoPi Neo 3 Carrier board

This board is designed to enhance the FriendlyElec NanoPi Neo 3 board with features suitable for a "server" style deployment. It uses a ESP32 as a BMC.

Features provided:
 - RTC clock 
 - Wired Ethernet interface
 - Gated power supply

## Motivation

Most SBC platforms lack the features needed for a rack style deployment where you can power cycle the board or get a remote console to debug what went wrong.
The ESP32 uC is fairly popular, but the reason behind selecting it to act as a BMC is that is one of the cheapest uCs equipped with a Ethernet PHY.

## Hardware overview
 (Diagram)
