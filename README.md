# pharma-tablet-starwheel
Continuous Manufacturing Tablet Testing System 
# Pharma Tablet Conveyor Belt

A conveyor automation system designed to transport and sort pharmaceutical tablets with consistent speed, stability, and safety. Includes CAD designs, electronics wiring, firmware, and demo videos.

---

## 🚀 Overview
This system moves tablets along a controlled conveyor belt using a motor-driven mechanism with guides, rollers, and optional counting/sorting sensors. Built to mimic small-scale industrial automation used in pharmaceutical production.

---

## 🎥 Demo
(Add GIF or link to your demo video here)

---

## 🛠️ Hardware Components
- Motor: (specify model)
- Motor driver: L298N / TB6612 / custom
- Microcontroller: Arduino / ESP32
- Frame: 3D-printed parts + aluminum rails
- Sensors: IR break beam / optical sensor (for counting)
- Power: 12V supply

Full Bill of Materials in `/hardware/BOM.csv`.

---

## 📐 CAD Files
All custom-designed components are in `/cad`.

Include:
- Belt assembly  
- Roller housings  
- Frame supports  
- Motor mount  
- Sensor brackets  

---

## 🔌 Wiring Diagram
![Wiring Diagram](docs/wiring-diagram.png)

---

## 🧠 Software & Firmware
Firmware lives under `/firmware`.

Software includes:
- Motor control loop
- Speed regulation
- Optional tablet counting logic
- PID tuning (if used)

---

## 🧪 Testing & Results
See `/results` for:
- Speed measurements  
- Stability tests  
- Counting accuracy (if applicable)  

---

## 📚 Future Improvements
- Add camera-based tablet detection
- Add sorting mechanism
- Add hopper feeder
- Add adjustable speed control via UI

---
