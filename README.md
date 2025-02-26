# STM32H7 based isolated simultaneous data acquisition system

This repository includes PCB-project files for a STM32 based isolated DAQ-System

# Board Features

- MCU: STM32H747IGT6, ARM Cortex M7 with 480MHz and ARM Cortex M4 with 240 MHz
- External memory: 1x 64 Mbit SDRAM, 1x 128 Mbit  QSPI Flash
- USB: USB 2.0 Transceiver Speeds up to 480 Mbit/s (HS), USB-C compatible Interface
- USB: Fullspeed 12 MBit/s
- Debug: Serial-Wire-Debug
- ADC: ADC128S052 12-Bit, 500-kSPS, 8-Channel SAR ADC with single-ended inputs and serial interface with a cutoff frequency of 212 kHz (first order RC-Lowpass)
- Input HARTING 09221326921 32 Position 2.54 mm pitch Horizontal Connector compatible with HARTING 09272326801

# Applications:

- Microphone Arrays
- Ultrasound
- Audio Analyzer
- Multi redundant Sensor Arrays for multi sensor data fusion applications
- Music pickups (Guitars, ...)
- Other Embedded Data Aqcuisition Systems

# Absolute Maximum Ratings

- Supply Voltage: +5V0 to +5V5 (recommended: +5V0) USB feeded
- ADC input Voltage: up to +3.3 V

# Manufacturing Information

- Length = 100mm, Width = 75mm, Thickness = 1.6 mm
- Layers = 6
- Min. Via Hole diameter = 0.3 mm
- Via-Type: Epoxy Filled and Capped
- Impedance Control: JLC06161H-3313
- Surface Finish: ENIG
- Material Type: FR-4 TG155

# Progress

- Schematic design: complete
- Layouting: complete
- Manufacturing & assembly: In progress
- Bring-Up: In progress

I make no guarantees as to device funtionality. Please review the components, schematics carefully before production.


![test](https://github.com/myildirim6198/STM32BasedSimultaneusDAQSystem/blob/main/Images/PictureDAQSystem.png?raw=true)

