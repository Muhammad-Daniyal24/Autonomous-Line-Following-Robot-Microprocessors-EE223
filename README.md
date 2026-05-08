# Autonomous Line-Following Robot – PIC18F4550

An autonomous line-following robot developed as part of the **Microprocessors (EE223)** course.  
The project focuses on building a robot from scratch using the **PIC18F4550 microcontroller**, without relying on Arduino or ESP32-based shortcuts.

> **Status:** Work in Progress  
> Currently, this repository contains the project demo/video. Code, circuit details, and full documentation will be added as the project progresses.
> [LinkedIn Project Reference](https://www.linkedin.com/posts/muhammad-daniyal-329476374_nerc2026-robotics-gikinstitute-activity-7453769386647048192-jSb_?utm_source=share&utm_medium=member_desktop&rcm=ACoAACR41TYBBa4etrlKaCGe5Jsc3fsBmPbSxT8)
## Project Overview

This project involves designing and developing an autonomous robot capable of following a line, detecting junctions, navigating multi-path arenas, and responding to obstacles.

The main challenge of the project is working directly with the **PIC18F4550** microcontroller, which requires low-level hardware control, manual circuit integration, sensor calibration, and firmware development in C.

## Current Progress

So far, the robot has successfully completed key milestone tasks, including:

- Motor control testing
- Sensor calibration
- Basic line-following behavior
- Junction detection logic
- Turn handling
- Obstacle detection
- Milestone demo run

The full project is still under development, and additional updates will be added soon.

## Key Features

- Autonomous line-following navigation
- Junction detection for multi-path arenas
- Custom turn logic for path selection
- Interrupt-driven PWM for motor speed control
- IR sensor-based line sensing
- Ultrasonic obstacle detection
- Custom motor driver and power regulation setup
- Hardware and firmware debugging through multiple milestones

## Hardware Components

- PIC18F4550 Microcontroller
- L298N Motor Driver
- TCRT5000 IR Sensors
- HC-SR04 Ultrasonic Sensor
- LM2596 Buck Converter
- 4WD Robot Chassis
- DC Motors
- Power Supply Module
- Jumper wires and soldered connections

## Tools and Technologies

- Embedded C
- MPLAB XC8
- PIC18F4550
- PWM Motor Control
- Interrupt-based Programming
- Sensor Interfacing
- Motor Driver Circuit Design
- Hardware Debugging

## Repository Contents

This repository currently includes:

- Project demo/video
- Initial project files and updates

Planned additions:

- Source code
- Circuit diagrams
- Component connection details
- Final project documentation
- Testing results
- Full demo videos

## Technical Highlights

### PIC18F4550-Based Control

The robot is controlled using the PIC18F4550 microcontroller, requiring direct configuration of pins, timers, interrupts, and PWM logic.

### Line Sensing

TCRT5000 IR sensors are used to detect the line and help the robot stay on track during movement.

### Junction Detection

The robot includes logic to identify intersections and avoid counting the same junction multiple times.

### Motor Speed Control

Interrupt-driven PWM is used to control motor speed and improve movement accuracy.

### Obstacle Detection

An HC-SR04 ultrasonic sensor is used to detect obstacles and improve safety during navigation.

### Power Regulation

An LM2596 buck converter is used to regulate voltage for stable hardware performance.

## Project Information

**Course:** Microprocessors  
**Project Type:** Academic / Hardware Project  
**Domain:** Embedded Systems, Robotics, Microcontroller Programming

## Learning Outcomes

This project helped develop practical understanding of:

- Low-level microcontroller programming
- Embedded C development
- Sensor calibration and interfacing
- Motor driver integration
- PWM-based motor control
- Hardware debugging
- Autonomous robot logic
- Real-time decision-making in embedded systems

## Future Updates

- Upload complete source code
- Add schematic/circuit diagrams
- Add final robot demo
- Add explanation of junction detection logic
- Add setup and wiring instructions
- Add milestone-wise development notes
