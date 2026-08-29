# ppg-analog-front-end
Analog front-end and PCB design for a wearable PPG heart-rate sensing system using photodiode signal conditioning, filtering, ADC, and MCU integration.
A wearable photoplethysmography (PPG) signal acquisition project focused on analog circuit design, PCB development, and hardware validation.

## Project Goal

The goal of this project is to design and build an analog front-end capable of acquiring a PPG signal from a photodiode and preparing the signal for digital processing.

The project is being developed from circuit simulation through breadboard prototyping and custom PCB implementation.

## System Overview

Photodiode → Analog Front-End → ADC → Microcontroller

The analog front-end will include:

- Photodiode signal acquisition
- Transimpedance amplification
- Signal filtering
- Signal conditioning
- ADC interfacing
- PCB implementation

## Design Process

The project follows an iterative engineering workflow:

1. Define system requirements
2. Analyze and design the circuit
3. Simulate using LTspice
4. Prototype and test the circuit
5. Design the PCB using KiCad
6. Manufacture and assemble the PCB
7. Validate the hardware through measurements
8. Revise the design based on test results

## Tools

- KiCad
- LTspice
- Oscilloscope / Analog Discovery
- Arduino
- SPICE simulation

## Project Status

🚧 **Work in Progress**

Currently developing and validating the analog front-end before PCB implementation.

## Repository Structure

- `hardware/` — KiCad schematic and PCB design
- `simulation/` — LTspice simulations
- `firmware/` — Microcontroller firmware
- `measurements/` — Experimental measurements and test results
- `docs/` — Design documentation
- `images/` — Project images and PCB renders
