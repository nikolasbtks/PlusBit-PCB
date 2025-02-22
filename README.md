# PlusBit-PCB

## Description

This project demonstrates a custom 4-layer PCB containing the STM32F446RCT6 and ESP32-WROOM-32E microcontrollers. This board can be used for embedded development applications using multiple peripherals.

## Components

1. Microcontroller: ATmega4809
   - 6 KB SRAM and 48 MB Flash
   - 20 MHz clock speed 
   
3. USB Connectivity:
   - USB Type-C for data and power 
   - USBLC6-2SC6 for ESD protection

4. Power Supply: LM3670MF-3.3 
   - Voltage regulator for stable 3.3V output
  
5. Headers:
   - UPDI header for debugging
   - GPIO, I2C, SPI and USART headers for external connections

6. Memory: AT24CS32-STUM
   - 32 Kbit of EEPROM storage
   - Non-volatile memory storage expansion

8. Sensor: TC1047xNB
   - Analog voltage output, propotional to temperature

## Disclaimer

This project is currently in **testing phase**. The provided documentation is shared for prototyping and learning purposes. If you choose to manufacture and use the board, please proceed with care, as it has not yet been fully validated.

## Schematic and PCB Design

The board was designed using Altium Designer. Files from the PCB design can be found in the **hardware** folder for board manufacture. This folder includes:

- PCB Schematic 
- PCB Layout

Below is a 3D render of the PCB design:


## How to Use

1. Power the board
   - Use a USB Type-C cable to power the board.
     
2. Microcontroller Programming:
   - Use STM32CubeIDE or any other platform to program the microcontroller.

3. Peripheral Access
   - Use the GPIO or SPI headers to connect peripherals.
