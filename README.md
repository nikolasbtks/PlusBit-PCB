# PlusBit-PCB

## Description

This project demonstrates a custom 4-layer PCB containing the STM32F446RCT6 and ESP32-WROOM-32E microcontrollers. This board can be used for embedded development applications using multiple peripherals.

## Components

1. Microcontroller: STM32F446RCT6
   - 256 KB SRAM and 512 KB Flash
   - Up to 180 MHz clock speed
  
2. Wireless Microcontroller: ESP32-WROOM-32E
   - 520 KB SRAM and 4 MB Flash
   - Wi-Fi and Bluetooth
   
3. USB Connectivity:
   - USB Type-C for data and power 
   - TPD2E001DRSR for ESD protection

4. Power Supply: TPS62740DSSR
   - Step-down regulator for stable 3.3V output
   - Support input voltage 2.2V to 5.5V
  
5. Headers:
   - GPIO, and SPI headers for external connections

6. Memory: FM24W256-G
   - 256 Kbit Ferroelectric RAM storage
   - Non-volatile memory storage

7. Security: ATECC608B-MAHDA-S
   - Hardware-based encryption and storage for keys
   - Support for cryptographic authentication
  
8. External Flash Storage: SST26VF016BT-104I/SM
   - 16 Mbit Flash Memory
   - High-speed read operations

9. Sensor: MCP9808-E/MS
   - Digital temperature output
     
## Disclaimer

This project is currently in **testing phase**. The provided documentation is shared for prototyping and learning purposes. If you choose to manufacture and use the board, please proceed with care, as it has not yet been fully validated.

## Schematic and PCB Design

The board was designed using Altium Designer. Files from the PCB design can be found in the **hardware** folder for board manufacture. This folder includes:

- PCB Schematic 
- PCB Layout
- Gerber Files
- Assembly Files

Below is a 3D render of the PCB design:

![image](https://github.com/user-attachments/assets/e9248570-ea6a-4b46-a66e-19c90ab99935)

## How to Use

1. Power the board
   - Use a USB Type-C cable to power the board.
     
2. Microcontroller Programming:
   - Use STM32CubeIDE or any other platform to program the microcontroller.

3. Peripheral Access
   - Use the GPIO or SPI headers to connect peripherals.
