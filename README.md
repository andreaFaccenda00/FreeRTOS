# FreeRTOS Real-Time Application on STM32G4

## Overview

This repository contains a real-time embedded software project based on **FreeRTOS** for the **STM32G4 series microcontroller**. The project demonstrates practical implementation of real-time scheduling, task synchronization, and peripheral management using FreeRTOS APIs, suitable for various embedded applications requiring precise timing and deterministic behavior.

## Features

- **STM32G4 MCU Support:** Optimized for STM32G4 series microcontrollers.
- **FreeRTOS Integration:** Real-time task scheduling, inter-task communication, and synchronization mechanisms.
- **Peripheral Management:** Examples of using peripherals (GPIO, USART, ADC, TIMERS) within RTOS tasks.
- **Low latency & deterministic performance:** Suitable for real-time control and industrial applications.

## Hardware Requirements

- STM32G4 development board (e.g., NUCLEO-G474RE).
- ST-LINK debugger/programmer.

## Software Requirements

- STM32CubeIDE or equivalent IDE (supporting STM32CubeMX).
- STM32CubeG4 HAL libraries.
- FreeRTOS kernel (provided with STM32Cube).

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/yourusername/freertos-stm32g4-project.git
```

### Building and Running

1. Open STM32CubeIDE and import the cloned project.
2. Configure your hardware settings (pin mappings, clock settings) if needed using STM32CubeMX integrated within STM32CubeIDE.
3. Build the project and flash the binary to the STM32G4 board.
4. Run the code and monitor execution via serial terminal or debugger.

## Project Structure

```
freertos-stm32g4-project/
├── Core
│   ├── Inc
│   │   ├── FreeRTOSConfig.h
│   │   └── main.h
│   └── Src
│       ├── main.c
│       ├── freertos.c
│       └── tasks.c
├── Drivers
│   └── STM32G4xx_HAL_Driver
├── Middlewares
│   └── FreeRTOS
├── STM32CubeIDE
│   └── project files
└── README.md
```

## Contribution

Feel free to submit pull requests for improvements, new features, or fixes. Please ensure your changes are well-tested and documented.

## License

Distributed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author

- [Your Name](https://github.com/yourusername)
- Contact: [your.email@example.com](mailto\:your.email@example.com)

---

Enjoy coding your real-time STM32G4 applications with FreeRTOS!

