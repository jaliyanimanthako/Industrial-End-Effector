
# Industrial End Effector for Automated Pick and Place Robots

This repository contains the hardware and software documentation for an industrial end effector designed for automated pick and place robots. The project integrates ToF (Time-of-Flight) sensors with a vacuum gripper, facilitating precise orientation detection and efficient communication with robot control panels.

## Overview

The project focuses on:
- Integrating ToF sensors (VL53L0X) for accurate measurement of box yaw and pitch angles.
- Using Modbus protocol over USB for seamless data transmission.
- Designing a robust PCB layout and enclosure to optimize space and ensure reliable operation in industrial environments.

## Features

- **Modbus Protocol Integration**: Enables reliable serial communication between the end effector and robot control panels.
- **ToF Sensors (VL53L0X)**: Facilitates precise box orientation detection essential for pick and place operations. 
  - *Library Usage*: Includes a detailed comparison between library usage and direct register-level programming for optimizing memory usage.
- **MAX485 TTL to RS485 Converter Module**: Converts TTL signals for long-distance communication.  
- **USB to RS485 Communication Module**: Used for debugging and monitoring via PC.

  ![rs485](https://github.com/jaliyanimanthako/Industrial-End-Effector-for-Automated-Pick-and-Place-Robots/assets/161110418/92b3b14d-f96a-4ae2-8b6d-2e325f05c642)

- **PCB Design**: Optimized layout for component integration and space efficiency.

![WhatsApp Image 2024-06-18 at 14 25 22_f2b9fc5d](https://github.com/jaliyanimanthako/Industrial-End-Effector-for-Automated-Pick-and-Place-Robots/assets/161110418/69982c36-3216-4f25-a3a1-138672eadd46)

  
- **Enclosure Design**: Ensures secure attachment and robust mechanical strength for various vacuum gripper sizes.
  - *Adjustable Design Challenges*: Discusses challenges and solutions related to accommodating different vacuum gripper sizes.
  - *Final Design*: Details the chosen enclosure design tailored for specific vacuum gripper models.

## Components

- **Microcontroller**: ATMEGA2560-16AU for data handling and communication.
- **Multiplexer**: PCA9546ADG4 manages I2C signals from multiple ToF sensors.
- **Crystal Oscillator**: ABLS2-16.000MHZ-D4Y-T provides stable clock signal.
- **Capacitors, Resistors, LEDs**: Essential components for power management, circuit configuration, and status indication.
- **Headers and Connectors**: Facilitate external connections and USB connectivity.

## Usage

1. **Setup**:
   - Connect the ToF sensors and components as per the hardware documentation.
   - Ensure proper power supply and USB connectivity for data transmission.

2. **Programming**:
   - Use the provided software libraries or customize firmware based on project requirements.
   - Implement Modbus communication protocols for seamless integration with robot control systems.

3. **Testing and Debugging**:
   - Utilize Modbus Poll software for monitoring data transmission and debugging.
   - Verify sensor accuracy and functionality before deployment.

## Enclosure Design

The enclosure design ensures:
- Secure attachment and mechanical strength suitable for various vacuum gripper models.
- Dedicated mounting places for ToF sensors (VL53L0X) to avoid interference with gripper functionality.
- Features like air vents for heat dissipation and mounting bosses for PCB, ensuring robustness and ease of access.

</p center>
 <img src = https://github.com/jaliyanimanthako/Industrial-End-Effector-for-Automated-Pick-and-Place-Robots/assets/161110418/a179bfe3-aa3e-4430-b7ed-a4d9d93666e1>
 </p>

 ![image](https://github.com/jaliyanimanthako/Industrial-End-Effector-for-Automated-Pick-and-Place-Robots/assets/161110418/8372e076-9fe1-44b0-b545-bae7987a9e8c)

