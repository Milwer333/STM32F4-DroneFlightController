# STM32F4-DroneFlightController
#### STM32F4-based drone flight controller designed from scratch.

This is my first ever attempt at designing and assembling a functional Flight Controller. The design is mostly a result of reverse-engineering of commertial products and deep research of the inner-workings of a drone.

**The board is a project for the university**. Designed in Altium Designer. Manufactured by JLCPCB. Assembled by hand.
___

#### The board consists of:
* STM32F405 microcontroller
* MPU-6000 6-axis IMU
* Hybrid construction (Flight Controller & Power Distribution Board)
* USB Type-C
* SBUS inverter
* Debugging tools
* Designed with Betaflight support in mind
* Test firmware (STM32CubeIDE)
___

**Disclaimer:** The flight controller prototype is currently missing the IMU unit due to global semiconductor shortage

BSD 3-Clause License - Copyright (c) 2022, Miłosz Werner - All rights reserved.
