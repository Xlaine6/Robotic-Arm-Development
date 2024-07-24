# Bluetooth-Controlled Robotic Arm

This project implements a 4-jointed robotic arm that can be controlled wirelessly via Bluetooth using an Android application. The robotic arm serves as an interactive prototype inspired by robotic systems used in industrial, manufacturing, and healthcare industries.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Hardware Requirements](#hardware-requirements)
- [Software Requirements](#software-requirements)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Safety Information](#safety-information)
- [Contributing](#contributing)

## Overview

The robotic arm utilizes 4 servo motors, a Bluetooth module, and an Arduino board to control the flexible movement of the arm parts. Users can control and steer the robotic arm through a custom-developed mobile application, allowing for rotation and object manipulation.

## Features

- 4-jointed robotic arm with flexible movement
- Wireless control via Bluetooth
- Custom Android application for controlling the arm
- Interactive LCD display for user introduction
- 3D-printed arm components

## Hardware Requirements

- 2x Arduino Uno boards
- 2x Breadboards
- 4x Servo Motors (SG90)
- 1x HC-06 Bluetooth Module
- 1x 16x2 LCD Character Display
- 1x Potentiometer
- 3x Resistors (220Ω)
- Jumper wires
- USB 2.0 Cable
- 3D-printed arm components (or alternative materials)

## Software Requirements

- Arduino IDE
- MIT App Inventor (for Android application development)
- Android device for running the control application

## Setup and Installation

1. Assemble the circuits according to the provided circuit diagrams.
2. Connect the Arduino boards to your computer using USB cables.
3. Upload the provided code to each Arduino board using the Arduino IDE.
4. 3D print the robotic arm components or use alternative materials to construct the arm.
5. Assemble the physical robotic arm, connecting the servo motors to the appropriate pins on the Arduino.
6. Install the custom Android application on your Android device.

For detailed assembly instructions and code explanations, please refer to the project documentation.

## Usage

1. Ensure that Bluetooth is enabled on your Android device.
2. Open the custom Android application and connect to the HC-06 Bluetooth module.
3. Use the four horizontal sliders in the app to control each joint of the robotic arm.
4. The LCD display on the Arduino setup will show a welcome message.

## Safety Information

- Avoid touching equipment or cables that have come in contact with liquids.
- Keep hands away from exposed wires connecting the Robotic Arm to the Arduino.
- Maintain stability with the robotic arm to ensure it doesn't lose balance.
- Handle the mobile phone used for remote control carefully.
- Ensure that the Bluetooth module is connected to 3.3V instead of 5V to avoid damage.

For more detailed safety instructions, please refer to the project documentation.

## Contributing

Contributions to improve the project are welcome. Please feel free to fork the repository, make changes, and submit pull requests.
