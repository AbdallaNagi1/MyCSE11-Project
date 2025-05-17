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
- 4-digit 7-segment display (common anode)
- 74HC595 shift register
- Potentiometer (as analog voltage source)
- Push buttons (S1 for reset, S3 for voltage)
- Basic resistors and breadboard wiring

---

## 📁 Report



---

## 🧠 How It Works
- Timer starts on boot and counts every second.
- Button **S1** resets the timer.
- Button **S3** switches display between MM:SS and voltage (scaled).
- Voltage values are scaled and displayed as X.XX (e.g., 2.47V → “2.47”).
- Internally tracks min and max voltage values.

---

## 🧪 Features
- Accurate timer display (MM:SS)
- Real-time voltage measurement
- Proper 7-segment encoding for all digits
- Uses shift registers to drive display efficiently
- Clean code and modular structure using `mbed`

---

## 📜 Report
The full report is included under the `/docs` folder as a PDF file.

---

## 👨‍💻 Developed By
**Abdulla Nagi**  
Ain Shams University – Mechatronics Department  
Spring 2025

---

## 📝 License
This project is for **educational and academic** purposes only.

