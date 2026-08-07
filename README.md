# ESP32-Servo-Web-Control
## Overview

This project uses an ESP32 as a Wi-Fi Access Point to control a servo motor through a web interface. Users can open or close the servo using two buttons, while green and red LEDs indicate the current status. The project was implemented and tested in both Wokwi simulation and real hardware.

## Project Features

- Controls a servo motor through a web interface.
- Uses the ESP32 as a Wi-Fi Access Point.
- Includes Open and Close control buttons.
- Uses green and red LEDs to indicate the servo status.
- Implemented and tested in both Wokwi simulation and real hardware

## Components Used

- ESP32 Development Board
- Micro Servo Motor (SG90)
- Green LED
- Red LED
- 2 × 220 Ω Resistors
- Breadboard
- Jumper Wires

## Circuit Connections

- Servo motor signal → GPIO 23
- Servo motor VCC → 5V
- Servo motor GND → GND
- Green LED → GPIO 18 (through a 220 Ω resistor)
- Red LED → GPIO 19 (through a 220 Ω resistor)
- All components share a common GND.

## Wokwi 

### Simulation

https://github.com/user-attachments/assets/d3df25f8-0999-4525-97bd-24922f527719

### Project Link

https://wokwi.com/projects/471562414456461313

## Hardware 

### Circuit Diagram

<img width="1353" height="1162" alt="WhatsApp Image 2026-08-07 at 2 42 43 AM" src="https://github.com/user-attachments/assets/1b28b22c-c9ec-4493-b69a-90e792e8a0e8" /> 

### Demo



https://github.com/user-attachments/assets/011b9086-65d6-4560-8255-246b8190c6c4

Note: The green LED uses a *10 kΩ resistor* in the hardware 

### Source Code 
The ESP32 source code is available in the Servo_Web.ino file.

## Project Auther
Hessah Safar Alharthi
