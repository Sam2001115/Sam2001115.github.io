# Sameer Appasa's Engineering Portfolio
**Electrical Engineering Student | IoT & Embedded Systems**

---

## 🛠 Technical Toolkit
* [cite_start]**Embedded Systems:** ESP32 DevKit, Arduino, OUSB Hardware/Simulation[cite: 1].
* **Languages:** C++, Python, Java, HTML.
* **Software:** Multisim Live, VS Code, Git.
* **Protocols:** Telegram Bot API, I2C, Wi-Fi (HTTP).

---

## 🚀 Key Projects

### 1. Autonomous Surface Rover
* **Objective:** Built an automated rover to clean hardwood floors using custom-designed gear systems for high torque.
* **Core Tech:** Arduino, 130 DC Motors, Ultrasonic Sensors.
* **Key Achievement:** Developed non-blocking real-time logic to handle sensor feedback and motor control simultaneously.

### 2. IoT Room Security Monitor
* **Objective:** Remote monitoring system to detect unauthorized entry using the ESP32.
* **Core Tech:** ESP32, Telegram Bot API, I2C OLED Display.
* **Key Achievement:** Integrated a "Healthcheck" heartbeat system to send email alerts if the device loses power or connection.

### 3. OUSB Process Control System
* [cite_start]**Objective:** Developed a C++ command-line tool for register-level hardware interaction and decision logic[cite: 1].
* [cite_start]**Core Tech:** C++, Bitwise Manipulation, OUSB Simulator[cite: 1].
* [cite_start]**Key Achievement:** Implemented a robust error-handling hierarchy (P, X, R, V, H, Y) to validate hardware inputs and communication integrity[cite: 1].

---
[LinkedIn] | [GitHub] | [Email]

# Project Deep Dive: Autonomous Cleaning Rover

## ⚙️ The Engineering Challenge
Standard 130 DC motors lack the torque required to move a chassis across carpet or uneven hardwood when weighted with cleaning apparatus. 

### Custom Mechanical Solution
To overcome this, I designed and fabricated a **custom gear reduction system**. This increased the mechanical advantage, allowing the low-torque motors to drive the platform reliably under load.

## 🧠 Control Logic & Hardware
* **Controller:** Arduino Uno / ESP32
* **Sensors:** HC-SR04 Ultrasonic Sensors
* **Actuators:** Dual 130 DC Motors with L298N Driver

### Real-Time Obstacle Avoidance
I implemented a "ping-and-pivot" logic. Instead of using basic delays, the firmware continuously polls the ultrasonic sensor. If an object is detected within 20cm, the rover executes a timed reverse-and-turn maneuver.

## 🛠 Lessons Learned
* **Power Management:** Learned how to handle voltage drops caused by motor inrush current.
* **Signal Noise:** Implemented basic filtering to prevent "ghost" obstacles from triggering the sensors.

---
[← Back to Home](index.md)
