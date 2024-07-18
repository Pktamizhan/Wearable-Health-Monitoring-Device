# Wearable Health Monitoring Device

This project is a wearable health monitoring device developed using an ARM Cortex-M microcontroller. It monitors heart rate and temperature using ECG and temperature sensors, processes the signals, and transmits the data over a serial interface.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Hardware Requirements](#hardware-requirements)
- [Software Requirements](#software-requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction

The wearable health monitoring device aims to provide continuous monitoring of heart rate and body temperature. The device is designed to be low-power and portable, making it ideal for non-invasive health monitoring applications.

## Features

- Monitors heart rate using an ECG sensor
- Measures body temperature using a temperature sensor
- Processes and transmits sensor data over UART
- Uses ARM Cortex-M microcontroller for low-power operation

## Hardware Requirements

- ARM Cortex-M microcontroller (e.g., STM32F4)
- ECG sensor
- Temperature sensor
- UART-to-USB adapter
- Breadboard and connecting wires

## Software Requirements

- STM32CubeIDE or any other compatible IDE
- STM32 HAL library
- Serial terminal software (e.g., PuTTY, Tera Term)

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/your-username/WearableHealthMonitoringDevice.git
   cd WearableHealthMonitoringDevice
Open the project in STM32CubeIDE:

Launch STM32CubeIDE.
Open the project directory you cloned.
Build the project:

Click on the build icon or press Ctrl+B to build the project.
Flash the microcontroller:

Connect your microcontroller to your PC.
Click on the debug icon or press F11 to flash the microcontroller.
Usage
Connect the sensors:

Connect the ECG sensor and temperature sensor to the respective ADC pins of the microcontroller.
Connect the UART-to-USB adapter to the microcontroller.
Monitor the output:

Open your serial terminal software and connect to the appropriate COM port with a baud rate of 115200.
You should see the heart rate and temperature data being displayed in the terminal.
Contributing
Contributions are welcome! Please fork the repository and use a feature branch. Pull requests are warmly welcome.

Fork the repository.
Create a new branch: git checkout -b feature-branch.
Make your changes and commit them: git commit -m 'Add some feature'.
Push to the branch: git push origin feature-branch.
Submit a pull request.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements
Special thanks to the open-source community for providing the tools and libraries used in this project.
Inspiration for this project came from various health monitoring research articles and projects.
