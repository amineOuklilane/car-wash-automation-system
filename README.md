# 🚗 Smart Car Wash Automation System  
### Arduino-Based Simulation Using Tinkercad

---

## 📌 Project Overview
This project presents the design and simulation of a **smart automated car wash system** using Arduino. The system detects the presence of a vehicle and executes a complete washing process based on user-selected modes.

The objective is to demonstrate key concepts in **automation, embedded systems, and sensor-based control** applied to a real-world industrial scenario.

---

## 🎯 Key Features
- Automated car detection using ultrasonic sensors  
- Multiple washing modes:
  - Water only  
  - Water + Soap  
  - Water + Soap + Wax  
- Sequential control of washing stations  
- Emergency stop using a main switch  
- LED-based simulation of system workflow  

---

## ⚙️ System Architecture

The system is divided into four functional stations:

- **Water Booth:** Initial cleaning using water  
- **Soap Booth:** Application of cleaning agents  
- **Soap + Wax Booth:** Final cleaning and polishing  
- **Drying Booth:** Air-based drying system  

Each station is automatically activated when a vehicle is detected within a محدد range using proximity sensors.

---

## 🛠️ Technologies & Components

### 💻 Technologies
- Arduino (Embedded C / Arduino IDE)  
- Tinkercad Simulator  

### 🔌 Hardware Components
- Arduino Uno  
- Ultrasonic Sensors (x4)  
- RGB LEDs (x2)  
- Standard LEDs  
- Resistors  
- Sliding Switch (main control)  
- Potentiometer  
- Connecting wires  

---

## 📷 Circuit Design
![Circuit](CarWashCircuit.png)

---

## 🎥 Demo Video
👉 Watch the simulation:  
https://youtu.be/FONUr4kZX1I

---

## 💻 Code
The Arduino source code is available in this repository:

- `Code.ino` → contains the full implementation of the system logic  

---

## 🧠 Implementation Details

- The system operates using a **continuous loop** to monitor:
  - Switch state (ON/OFF)  
  - Sensor inputs  

- When a vehicle is detected:
  - The corresponding station is activated  
  - LEDs simulate the real-world washing process  

- A **main switch** allows immediate shutdown of the system at any time (safety feature)

---

## 🚀 Future Improvements
- Integrate temperature sensors for system safety  
- Add emergency button with buzzer alarm  
- Replace polling with interrupt-based control  
- Add LCD display for user interface  
- Integrate IoT or mobile application control  

---

## 🌍 Project Context
This project was developed as part of my personal portfolio in Electrical Engineering, focusing on automation systems, embedded programming, and real-world industrial simulations.

---

## 👤 Author
**Amine Ouklilane**  
Electrical Engineering Student  

- Interested in Embedded Systems, Automation, and Smart Technologies  
- Currently building a strong portfolio for international academic and career opportunities  

---

## 💡 Portfolio Note
This project reflects my ability to design and simulate **automated systems using embedded technologies**, with a focus on practical applications and scalable solutions.
