# STM32 Embedded Projects

> A long-term collection of STM32 embedded projects, experiments, drivers, communication protocols and practical applications.

## 🎯 Project Goal

This repository records my hands-on learning path from basic MCU programming to complete embedded systems.

The main platform is **STM32F103ZET6**, with **STC89C52** as a complementary 51 MCU platform for learning low-level MCU fundamentals.

## 🧰 Current Hardware

### MCU Platforms
- STM32F103ZET6 Elite Development Board
- STC89C52 Puzhong 51 Development Board

### Existing Modules
- MPU6050
- ESP8266
- OLED
- Breadboard

### Planned Expansion
- SPI TFT LCD
- RC522 RFID
- MAX485 / RS485
- HC-SR04 ultrasonic sensor
- SG90 servo
- 4×4 matrix keypad
- DS18B20
- TB6612FNG motor driver

## 🗺️ Learning Roadmap

```text
MCU Fundamentals
      ↓
GPIO / EXTI / UART / TIM / ADC
      ↓
I²C / SPI
      ↓
OLED / MPU6050 / RC522 / TFT
      ↓
PWM / Servo / Ultrasonic / Motor
      ↓
ESP8266 / Wi-Fi
      ↓
RS485 / Modbus RTU
      ↓
FreeRTOS
      ↓
Integrated Embedded Systems
```

## 📂 Project Structure

| Directory | Topic | Status |
|---|---|---|
| `01_GPIO_LED` | GPIO / LED | Planned |
| `02_KEY_EXTI` | Key input / External interrupt | Planned |
| `03_TIMER_PWM` | Timer / PWM | Planned |
| `04_OLED` | OLED / I²C | Planned |
| `05_MPU6050` | IMU / I²C | Planned |
| `06_TFT` | TFT / SPI / GUI | Planned |
| `07_RC522` | RFID / SPI | Planned |
| `08_RS485` | RS485 / Modbus RTU | Planned |
| `09_ESP8266` | UART / Wi-Fi | Planned |
| `10_SMART_ACCESS_CONTROL` | Integrated RFID access control | Planned |
| `11_ENVIRONMENT_MONITOR` | Integrated monitoring terminal | Planned |

## 🧪 Development Principles

Each project aims to document:

1. Project objective
2. Hardware list and wiring
3. Software environment
4. Peripheral configuration
5. Source code structure
6. Debugging process
7. Problems encountered and solutions
8. Demonstration results
9. Possible improvements

## 🛠️ Development Environment

- C / C++ where appropriate
- Keil MDK
- STM32 standard peripheral libraries and/or HAL, depending on the project
- Git / GitHub

## 📌 Notes

This repository is a continuously evolving personal embedded-systems lab. Early projects focus on understanding fundamentals; later projects emphasize reusable drivers, communication, RTOS and system-level integration.

## 📈 Progress

- [ ] STM32 GPIO fundamentals
- [ ] Interrupts and timers
- [ ] UART communication
- [ ] I²C and SPI
- [ ] Sensor drivers
- [ ] Display and GUI
- [ ] RFID
- [ ] RS485 / Modbus
- [ ] ESP8266 networking
- [ ] FreeRTOS
- [ ] Complete integrated project
