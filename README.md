# 🤖 Gesture-Controlled Robot Using Arduino

A wireless robotic system that responds to hand gestures for intuitive motion control. The project uses an **MPU6050 accelerometer/gyroscope** to detect hand orientation and transmits data via **nRF24L01 transceiver modules** to a receiver Arduino that drives **DC motors** through an **L293D motor driver**.

## 🔧 Tools & Technologies
- **Arduino UNO**
- **MPU6050 Sensor**
- **nRF24L01 Transceiver Modules**
- **L293D Motor Driver**, **DC Motors**
- **Arduino IDE**

## 🚀 Features
- Wireless communication between transmitter and receiver units
- Real-time gesture detection and mapping to robot motion
- Smooth control in forward, backward, left, and right directions
- Modular and easy to extend for more gestures or sensors

## 🧠 Future Enhancements
- Integrate obstacle avoidance using ultrasonic sensors
- Add Bluetooth/mobile control mode
- Implement PID-based motion stabilization

## 📷 Project Overview
The robot consists of two Arduino-based modules:
- **Transmitter Unit** – Captures hand gestures using MPU6050 and sends commands via nRF24L01.
- **Receiver Unit** – Interprets received data to drive motors through the L293D driver.

---
> Built as part of an embedded systems and robotics learning project.
