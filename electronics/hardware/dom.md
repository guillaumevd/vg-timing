# Bill of Materials (BOM) - VG-Timing Lap Timing System

This document contains the detailed list of components required for the VG-Timing lap timing system, organized by sections.

## Table of Contents

- [Microcontroller](#microcontroller)
- [RFID System](#rfid-system)
- [Memory](#memory)
- [GPS Module](#gps-module)
- [Long-Range Communication](#long-range-communication)
- [Controls](#controls)
- [Display](#display)

## Microcontroller

### NXP i.MX RT1170 Crossover MCU

The i.MX RT1170 series is a family of Arm Cortex-M7 and Cortex-M4 based crossover MCUs designed for high-performance embedded applications. The i.MX RT1170 is ideal for our project due to its high processing power, ease of programming, and extensive peripheral support.

- Manufacturer: NXP Semiconductors
- Part Number: MIMXRT1170xxxxA
- Core: Arm Cortex-M7 and Cortex-M4
- Operating Frequency: Up to 1 GHz (Cortex-M7), up to 400 MHz (Cortex-M4)
- Flash Memory: Up to 2 MB
- RAM: Up to 1 MB
- Package: LFBGA196

### Epson FA-238 Crystal Oscillator

The Epson FA-238 is a high-precision crystal oscillator used to provide a stable clock signal for the microcontroller.

- Manufacturer: Epson
- Part Number: FA-238
- Frequency: 24 MHz (Customizable)
- Package: SMD
- Operating Temperature: -40°C to +85°C

## RFID System

### Texas Instruments CC2500 Low-Cost Low-Power 2.4 GHz RF Transceiver

The CC2500 is a low-cost, low-power 2.4 GHz RF transceiver designed for low-power wireless applications. It is used for the RFID system to communicate with the transponders.

- Manufacturer: Texas Instruments
- Part Number: CC2500
- Operating Frequency: 2.4 GHz
- Interface: SPI
- Supply Voltage: 1.8 V - 3.6 V

### Maxim Integrated MAX9938 Low-Voltage, High-Accuracy Current-Sense Amplifier

The MAX9938 is a low-voltage, high-accuracy current-sense amplifier, used in the RFID system to detect the presence of transponders and measure their unique IDs.

- Manufacturer: Maxim Integrated
- Part Number: MAX9938
- Gain: 20 V/V
- Supply Voltage: 1.6 V - 5.5 V
- Interface: Analog

### Analog Devices ADL5243 Dual, Digitally Controlled Variable Gain Amplifier

The ADL5243 is a dual, digitally controlled variable gain amplifier used in the RFID system to adjust the loop power, ensuring optimal performance.

- Manufacturer: Analog Devices
- Part Number: ADL5243
- Gain Range: -6 dB to +42 dB
- Operating Frequency: 100 MHz - 4 GHz
- Interface: SPI
- Supply Voltage: 4.5 V - 5.5 V

### SMA Connector

The SMA connector is used to connect the loop antenna to the RFID system.

- Type: SMA Female
- Impedance: 50 Ohm

## Memory

### AT24C512 Two-wire Serial EEPROM

The AT24C512 is a 512-Kbit, 2-wire serial EEPROM that provides non-volatile memory storage for the lap timing system. It is used to store lap times and other relevant data.

- Manufacturer: Microchip Technology
- Part Number: AT24C512
- Memory Size: 512 Kbit
- Interface: I2C
- Supply Voltage: 1.7 V - 5.5 V

## GPS Module

### u-blox LEA-6T GPS Module

The u-blox LEA-6T is a high-performance GPS module that provides accurate time and position information. In our project, it is used for timestamping lap times.

- Manufacturer: u-blox
- Part Number: LEA-6T-0-01
- Channels: 50
- Update Rate: up to 5 Hz
- Interface: UART
- Supply Voltage: 2.7 V - 3.6 V

## Long-Range Communication

### Semtech SX1276 LoRa Transceiver

The SX1276 is a long-range, low-power LoRa transceiver that allows multiple VG-Timing devices to communicate with each other wirelessly at distances of up to 1.5 km.

- Manufacturer: Semtech
- Part Number: SX1276
- Operating Frequency: 860 MHz - 1 GHz
- Interface: SPI
- Supply Voltage: 1.8 V - 3.7 V

### SMA Connector

The SMA connector is used to connect the long-range communication antenna to the SX1276 transceiver.

- Type: SMA Female
- Impedance: 50 Ohm

## Controls

### Buttons

Three buttons (Up, Down, Select) are used to navigate the menu and adjust settings such as loop power and communication channel.

- Type: Tactile Push Button Switch
- Operating Force: 160 gf
- Travel: 0.25 mm

## Display

### Newhaven Display NHD-C12864WC-FSW-FBW-3V3-M Graphic LCD Module

The NHD-C12864WC-FSW-FBW-3V3-M is a 128x64 pixel graphic LCD module with a white LED backlight and a built-in controller. It is used to display relevant information and status updates.

- Manufacturer: Newhaven Display
- Part Number: NHD-C12864WC-FSW-FBW-3V3-M
- Resolution: 128x64 pixels
- Interface: SPI
- Supply Voltage: 2.7 V - 3.3 V
- Connector: 10-pin FFC/FPC

### FFC/FPC Connector

The FFC/FPC connector is used to connect the LCD module to the microcontroller.

- Type: 10-pin FFC/FPC connector
- Pitch: 0.5 mm
- Mounting Type: Surface Mount
