# CP2102 USB Type-C to UART Converter

A compact USB Type-C to UART converter based on the Silicon Labs **CP2102** USB-to-UART bridge IC. This board provides a reliable serial communication interface for programming, debugging, and data exchange with embedded systems.

## Features

- USB Type-C interface
- CP2102 USB-to-UART bridge
- TX and RX activity LEDs
- External UART header
- USB-powered operation
- Compact PCB design
- Designed using KiCad

## Hardware Specifications

| Parameter | Value |
|-----------|-------|
| USB Interface | USB Type-C |
| USB-to-UART IC | CP2102 |
| Supply Voltage | 5V (USB VBUS) |
| UART Signals | TX, RX, GND |
| Status LEDs | TX Activity, RX Activity |
| Design Tool | KiCad 9 |

## Overview

This project implements a USB Type-C to UART converter using the CP2102 USB-to-Serial bridge IC. The board allows communication between a computer and microcontroller-based systems through a standard UART interface.

The design includes:
- USB Type-C connector for power and data
- CP2102 USB-UART controller
- TX/RX status indication LEDs
- External UART header for easy interfacing
- Decoupling capacitors for stable operation

## Pinout

| Pin | Function |
|------|----------|
| TX | UART Transmit |
| RX | UART Receive |
| RST | Reset |
| VBUS | USB 5V Output |
| GND | Ground |

## Applications

- Microcontroller programming
- Embedded system debugging
- UART communication testing
- Serial data logging
- IoT device development
- Bootloader flashing


## Getting Started

1. Connect the board to a computer using a USB Type-C cable.
2. Install CP2102 drivers if required by your operating system.
3. Connect TX, RX, and GND to the target device.
4. Open a serial terminal application.
5. Select the detected COM port and start communication.

## Software Compatibility

- Windows
- Linux
- macOS

## Future Improvements

- USB ESD protection
- RTS/CTS hardware flow control
- Auto-reset circuitry for development boards
- Additional status indicators
- Enhanced protection circuitry

## Author

**Abhishek B Kumbar**  
Electronics and Communication Engineering (ECE)

## License

This project is licensed under the MIT License.
