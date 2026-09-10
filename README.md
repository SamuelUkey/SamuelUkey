# ESP32 Battery Monitoring System

## Overview

A battery monitoring system based on the ESP32 that measures battery
voltage, processes the ADC readings, and displays the measured value
on an OLED display.

The project focuses on ADC measurement, voltage scaling, calibration,
I²C communication, and hardware implementation.

## System Architecture

Battery
   ↓
Voltage Divider
   ↓
ESP32 ADC
   ↓
Voltage Calculation
   ↓
OLED Display

## Hardware

- ESP32
- OLED Display
- Resistors for voltage divider
- Battery input
- Protection components

## Hardware Design

[Insert schematic]

[Insert PCB]

[Insert 3D PCB view]

## Firmware

The ESP32 reads the analog voltage through its ADC, converts the
reading into the corresponding battery voltage, and updates the
OLED display.

## Testing

| Reference | Measured |
|---|---:|
| Multimeter | X.XX V |
| ESP32 | X.XX V |
| Error | X.XX % |

## Problems & Debugging

### ADC reading error
...

### OLED communication issue
...

## Result

[Insert photo of working hardware]

## Repository Structure

```text
hardware/
firmware/
schematic/
pcb/
images/
documentation/
