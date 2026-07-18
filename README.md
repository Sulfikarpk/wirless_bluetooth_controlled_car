# 🚗 Wireless Bluetooth Gesture Controlled Car

A **Wireless Bluetooth Gesture Controlled Car** developed as a school project using **Arduino Uno**, **MPU6050 Gyroscope/Accelerometer Sensor**, and **HC-05 Bluetooth modules**. The project enables wireless control of a robotic vehicle through hand gestures, demonstrating embedded systems, sensor interfacing, Bluetooth communication, and motor control.

---

# 📖 Project Overview

The system consists of two separate units: a **Transmitter** and a **Receiver**.

The **Transmitter Unit** uses an **Arduino Uno**, an **MPU6050 Gyroscope/Accelerometer**, and an **HC-05 Bluetooth module** configured as the **Master**. The MPU6050 detects the tilt and movement of the user's hand, and the Arduino processes this data to generate movement commands. These commands are transmitted wirelessly through Bluetooth.

The **Receiver Unit** consists of another **Arduino Uno**, an **HC-05 Bluetooth module** configured as the **Slave**, an **L298N Motor Driver**, and DC motors. The receiver Arduino interprets the incoming Bluetooth commands and controls the motors, allowing the car to move in real time according to the user's hand gestures.

---
# 🎥 Demonstration

part-1 testing 
https://youtube.com/shorts/T_PyylMDDD8

---

# 🎯 Objective

- Develop a wireless gesture-controlled robotic vehicle.
- Learn Bluetooth communication using HC-05 Master and Slave modules.
- Interface the MPU6050 sensor with Arduino.
- Control DC motors wirelessly using embedded programming.
- Demonstrate real-time embedded system communication.

---

# 🛠 Hardware Used

| Component | Purpose |
|-----------|---------|
| Arduino Uno (2) | Transmitter and Receiver Controllers |
| MPU6050 | Gesture Detection |
| HC-05 Bluetooth Modules (Master & Slave) | Wireless Communication |
| L298N Motor Driver | Motor Control |
| DC Motors | Vehicle Movement |
| Chassis & Wheels | Mobile Platform |
| Battery Pack | Power Supply |

---

# ⚙️ System Workflow

1. The MPU6050 sensor detects the user's hand movement and tilt.
2. The transmitter Arduino reads the sensor values.
3. Based on the detected gesture, movement commands are generated.
4. The HC-05 Bluetooth module (Master) transmits the commands wirelessly.
5. The HC-05 Bluetooth module (Slave) receives the commands.
6. The receiver Arduino processes the received data.
7. The L298N Motor Driver controls the DC motors.
8. The robotic car moves according to the user's hand gestures.

---

# 💻 Software Used

- Arduino IDE
- Embedded C

---

# ⭐ Key Features

- Wireless Bluetooth communication
- Gesture-based vehicle control
- MPU6050 motion sensing
- HC-05 Master-Slave communication
- Real-time motor control
- Embedded system integration

---

# 📚 What I Learned

- Arduino Programming
- Embedded C
- MPU6050 Sensor Interfacing
- Bluetooth Communication
- HC-05 Master-Slave Configuration
- Motor Driver Interfacing
- Wireless Embedded Systems
- Hardware Integration
- Embedded System Debugging

---

# 📁 source code

-reciver part(https://github.com/Sulfikarpk/wirless_bluetooth_controlled_car/blob/main/reciver.bin)

---

-transmitter part(https://github.com/Sulfikarpk/wirless_bluetooth_controlled_car/blob/main/transmitter.bin)

---

# 📁 Repository Structure

```
Wireless-Bluetooth-Gesture-Controlled-Car
│
├── Arduino_Transmitter/
├── Arduino_Receiver/
├── Images/
├── Videos/
├── README.md
└── LICENSE
```

---

# 👨‍💻 Author

**Sulfikar P.K.**

Embedded Engineer | Embedded Linux | Firmware Development | Robotics
