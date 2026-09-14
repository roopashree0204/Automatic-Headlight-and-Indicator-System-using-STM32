# Automatic-Headlight-and-Indicator-System-using-STM32
STM32-based automatic headlight and indicator system using ADC-based voltage sensing and LED control.

# Automatic Headlight and Indicator System using STM32

## Overview

An embedded automotive system that uses an STM32F103C8T6 microcontroller to read analog voltage from a 10 kΩ potentiometer and control three LEDs based on predefined ADC voltage ranges.

## Objective

To interface a potentiometer as an analog input with the STM32 microcontroller and control three LEDs according to different ADC voltage ranges, simulating an automatic headlight and indicator system.

## Hardware

- STM32F103C8T6 (Blue Pill)
- 10 kΩ Potentiometer
- Red, Green and Blue LEDs
- 330 Ω Resistors
- Connecting Wires

## Working

Potentiometer → ADC → STM32 Processing → GPIO Control → LED Indicators

The potentiometer generates a variable analog voltage based on its position. The STM32 ADC converts this voltage into a digital value, which is processed to control the LEDs according to predefined voltage ranges. :contentReference[oaicite:1]{index=1}

## Technologies Used

- STM32F103C8T6
- Embedded C
- ADC
- GPIO
- Analog Signal Processing
- LED Interfacing

## Simulation

![Simulink Model](images/simulink_model.png)

The Simulink model represents the analog input, ADC-based processing, and corresponding LED outputs.

## Hardware Implementation

![Hardware Implementation](images/hardware.jpg)

The system was implemented on a breadboard using the STM32 microcontroller, potentiometer, and three LEDs. The LEDs responded to changes in potentiometer position according to the programmed thresholds. :contentReference[oaicite:2]{index=2}

## Result

The STM32 successfully converted the potentiometer's analog voltage into digital values and controlled the LEDs according to the defined voltage ranges. The system responded in real time to changes in the potentiometer input. :contentReference[oaicite:3]{index=3}

## Documentation

The complete project documentation is available in the `docs/` folder.
