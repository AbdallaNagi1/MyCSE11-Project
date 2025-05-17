# Timer and Voltage Monitor - Final Project (CSE211s, Spring 2025)

## 📌 Overview
This is the final project for the Embedded Systems course (CSE211s).  
The project demonstrates a real-time **timer** and **voltage monitor** using a **4-digit 7-segment display**, **shift registers**, and **analog input** via a potentiometer.

### Key functionalities:
- Time display in MM:SS format
- Live voltage reading from a potentiometer (0–3.3V)
- Min/Max voltage tracking
- Button-controlled display switching (time vs. voltage)

---

## 📹 Demonstration Video
https://github.com/user-attachments/assets/63b13961-3ed6-4ddd-9880-2a0b03365cab
---

## 🔧 Components Used
- NUCLEO-F401RE development board
- Arduino Multifunction Shield (with built-in 4-digit 7-segment display, buttons, potentiometer)
- 74HC595 shift register (integrated on the shield)
- Onboard buttons:  
  - **S1** → Reset timer  
  - **S3** → Display voltage
- Onboard potentiometer for analog voltage input
---

## 📁 Report



---

## 🧠 How It Works
- Timer starts on boot and increments every second.
- Pressing **S1** resets the timer.
- Pressing **S3** toggles the display to show the live voltage.
- Voltage values are scaled and shown in X.XX format (e.g., 2.47V → “2.47”).
- Tracks and stores the minimum and maximum voltage values recorded.

---

## 🧪 Features
- Accurate timekeeping (MM:SS format)
- Real-time analog voltage monitoring
- Efficient 7-segment display control using a shift register
- Clean, modular C++ implementation using the `mbed` platform
- Debounced button functionality and responsive switching
---

## 📜 Report
[CSE211 Final Report.pdf](https://github.com/user-attachments/files/20265810/CSE211.Final.Report.pdf)
---

## 👨‍💻 Developed By
**Abdulla Nagi** - **Ahmed Othman** - **Amr Fakher**

Ain Shams University – Mechatronics Department  
Spring 2025

---

## 📝 License
This project is for **educational and academic** purposes only.

