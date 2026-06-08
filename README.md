# Automotive Dashboard

An embedded systems project implementing a CAN-based automotive dashboard using STM32 microcontrollers.  
Displays real-time vehicle parameters such as Speed, RPM, Gear, Time & Date, Indicator, and Temperature on an LCD, with CAN bus communication between modules.

---

## 🚀 Features
- CAN bus communication for real-time data exchange
- LCD display for speed, RPM, Gear, Time & Date, Indicator, and temperature
- Modular design for easy extension (add sensors or indicators)
- FreeRTOS tasks for concurrency and timing control

---

## 🛠️ Hardware Requirements
- STM32F429ZI (or compatible STM32 MCU)
- CAN transceiver module
- LCD display (I2C/SPI interface)
- LEDs and push buttons for alerts/controls
- Power supply and wiring harness

---

## 🛠️ Software Requirements
- STM32CubeIDE 
- STM32 HAL drivers
- Git for version control

---

## ▶️ Usage
1. Flash the firmware to the STM32 board.
2. Connect CAN transceiver and LCD.
3. Power up the system.
4. Observe real-time dashboard updates:
   - Speed and RPM values
   - Gear, Time & Date, Indicator, and temperature
   - Alerts on LCD and LEDs

---

## 📂 Project Structure
- `src/` → Source code files (CAN, LCD, FreeRTOS tasks)
- `include/` → Header files
- `Makefile` → Build automation
- `README.md` → Documentation

---

## 📖 Learning Goals
This project was built to practice:
- CAN bus protocol implementation
- Real-time task scheduling with FreeRTOS
- Embedded C programming with STM32 HAL
- LCD interfacing and data visualization

---

## 📜 License
This project is licensed under the MIT License.
