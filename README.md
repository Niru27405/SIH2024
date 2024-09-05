# SIH2024
Solar Tracking System
Overview
The Solar Tracking System is an intelligent, energy-efficient device designed to automatically track the sun's movement to optimize the energy output of solar panels. By using sensors and a PID controller, the system adjusts the orientation of the solar panels to maximize their exposure to sunlight throughout the day, increasing their efficiency and energy production.

This project is part of the Smart India Hackathon (SIH) and aims to contribute towards sustainable energy solutions.

Features

Automatic Sun Tracking: Adjusts the orientation of solar panels to follow the sun's position.
PID Controller: Ensures smooth and efficient movements of the solar panels by minimizing errors in tracking.
Real-Time Data Collection: Tracks panel position and sunlight intensity in real-time.
Energy Optimization: Maximizes the energy output of solar panels by maintaining optimal alignment with the sun.
Manual Override: Allows manual control for maintenance or special conditions.

System Architecture

Sensors: LDRs (Light Dependent Resistors) are used to detect the intensity of sunlight from different directions.
Microcontroller: A microcontroller (e.g., Arduino, ESP32) processes the sensor data and sends commands to the motors.
Motors: Servo or stepper motors adjust the angle of the solar panel based on sensor feedback.
PID Controller: A PID (Proportional-Integral-Derivative) controller is implemented to ensure precise and efficient panel movements.

Components

Light Dependent Resistors (LDRs): To sense sunlight intensity.
Microcontroller: Arduino/ESP32 for processing and control.
Motors: Servo or stepper motors for panel movement.
PID Controller: To control motor speed and position.
Solar Panel: To generate electricity from sunlight.
Power Supply: To power the components.

Hardware Requirements:
Arduino/ESP32 or any other microcontroller
4 x LDR sensors
2 x Servo motors/Stepper motors
Solar panel
Resistors, wires, and other electronic components
Power supply (Battery/Solar-powered)

Software Requirements:
Arduino IDE (for coding and uploading sketches)
PID control library (if applicable)
Serial monitor or external display (optional for debugging and monitoring)
