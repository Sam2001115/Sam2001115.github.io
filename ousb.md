# OUSB Process Control System
**Low-Level C++ Hardware Interface**

---

## 📋 The Engineering Challenge
The goal of this project was to develop a command-line interface (CLI) in C++ that interacts with the **OUSB (Open Universal Serial Board)** hardware simulator. The system must read 8-bit digital inputs (DIP switches) and 10-bit analog inputs (Potentiometers), perform logic comparisons, and update hardware registers accordingly.



## 🛠 Technical Implementation

### 1. Robust Error Precedence Hierarchy
To ensure system stability and prevent invalid data from reaching the hardware registers, I implemented a strict error-handling hierarchy. If multiple errors occur, the system reports only the highest-priority error:

| Code | Priority | Description |
|:---:|:---|:---|
| **P** | Highest | **Parameter Error:** Incorrect number of command-line arguments. |
| **X** | High | **Numerical Error:** Input is not a valid number (e.g., contains letters). |
| **R** | Medium | **Range Error:** Numerical value is outside the 0–255 8-bit limit. |
| **V** | Medium | **Validation Error:** Logic failure where Switch value < Potentiometer value. |
| **H** | Low | **Hardware Error:** The OUSB device failed to respond or is disconnected. |
| **Y** | Lowest | **System Error:** Internal logic or memory failure. |



### 2. Intelligent Data Validation
A key feature of my code is the `expocnentialcheck` function. Instead of relying on standard conversion tools that might fail silently, this function manually parses strings to validate:
* Numerical digits `0-9`.
* Scientific notation markers `E` or `e`.
* Decimal points and polarity signs `+/-`.

### 3. Bitwise Register Manipulation
The project required manipulating 8-bit binary strings to represent hardware states. I wrote logic to convert integer values into both **Standard Binary** and **Reverse Binary** formats to match the specific requirements of the OUSB LED registers.

## 🧠 Key Skills Demonstrated
* **C++ Systems Programming:** Managing data types and memory for hardware interaction.
* **Industrial Logic:** Implementing "Precedence" so the most dangerous errors are caught first.
* **Register-Level Control:** Direct manipulation of `PINC` and `ADC` values.

---
[← Back to Home](index.md)
