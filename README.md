# 🌊 Flood Detection Pole STM code

A real-time embedded system for detecting potential flood conditions using a combination of sensors and microcontrollers. Developed as part of the **Embedded System Laboratory (2110366)** course at **Chulalongkorn University (Semester 2, 2022)**.

## Project Overview

This prototype uses an STM32 NUCLEO-F411RE board to read environmental data from multiple sensors and transmit the processed results to both a PC (for debugging) and a NodeMCU (ESP8266) for potential IoT integration.

### Objectives
- Detect water level and height.
- Measure water flow velocity and direction.
- Transmit data for monitoring and future flood prediction.

---

## ⚙️ Hardware Components

| Component             | Description                            |
|----------------------|----------------------------------------|
| STM32 NUCLEO-F411RE  | Main microcontroller for data handling |
| NodeMCU (ESP8266)    | WiFi-enabled microcontroller for cloud communication |
| Ultrasonic Sensor    | Measures distance to water surface     |
| Water Level Sensor   | Detects water presence or depth        |
| Water Flow Sensor    | Calculates water velocity and direction |

---


