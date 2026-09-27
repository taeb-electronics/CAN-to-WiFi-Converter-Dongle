# CAN-to-WiFi Converter Dongle

An ESP32-based CAN-to-WiFi converter designed to provide wireless connectivity to CAN-enabled systems. The project combines CAN bus communication, Wi-Fi connectivity, embedded programming, and PCB design to enable monitoring and transfer of CAN data over a wireless network.

## Project Overview

Controller Area Network (CAN) is widely used in automotive, industrial automation, robotics, and embedded systems for reliable communication between electronic control units and devices.

This project explores the development of a compact CAN-to-WiFi interface that acts as a bridge between a CAN bus and a Wi-Fi network.

The ESP32 is used as the main controller because it provides both Wi-Fi connectivity and sufficient processing capability for handling communication between the CAN interface and the wireless network.

## Key Features

- CAN bus communication
- Wi-Fi connectivity using ESP32
- CAN-to-WiFi data bridging
- Embedded microcontroller-based architecture
- Custom PCB design
- Schematic design and PCB layout using KiCad
- Hardware-oriented communication interface
- Compact dongle-style hardware concept

## System Architecture

```text
             CAN-enabled Device
                     |
                     |
                CAN Bus
                     |
                     v
             +---------------+
             | CAN Interface |
             +---------------+
                     |
                     v
             +---------------+
             |     ESP32     |
             |               |
             | CAN Processing|
             | Wi-Fi Control |
             +---------------+
                     |
                  Wi-Fi
                     |
                     v
             +---------------+
             | Wi-Fi Network |
             +---------------+
                     |
                     v
          PC / Mobile / IoT System
