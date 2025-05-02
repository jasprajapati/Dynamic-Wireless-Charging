# ⚡ Dynamic Wireless Charging System for Electric Vehicles (EVs)

This repository showcases the design and simulation of a **Dynamic Wireless Charging (DWC)** system for electric vehicles using **MATLAB/Simulink**. The project explores how electric vehicles can be charged wirelessly while in motion, addressing range anxiety and reducing dependence on stationary charging stations.

---

## 📘 Abstract

Dynamic Wireless Charging (DWC) uses **resonant inductive power transfer** to deliver energy from coils embedded in roadways to EVs equipped with receiving coils. This system enables **on-the-go charging**, reducing battery size, cost, and overall charging downtime. Our simulation presents a realistic scenario integrating **power electronics, coil coupling, and battery charging dynamics**, using industry-standard SS compensation topology.

---

## 📁 Project Structure

- `SimulinkModel/` – Contains the complete simulation model of the DWC system  
- `Figures/` – Waveform outputs including voltage, current, SOC  
- `Documentation/` – Technical report, circuit design explanation, and methodology  

---

## 🧠 Key Features

- Full **AC-DC-AC conversion chain** using high-frequency inverters  
- **SS-compensated RIPT system** with realistic misalignment and air gap models  
- **MATLAB/Simulink simulation** for full system including:
  - Power transmission stage  
  - Coil coupling and energy transfer  
  - Battery charging using CC-CV profile  
- Performance metrics:
  - Efficiency: 88–92%  
  - Tolerance to misalignment: ±10 cm  
  - Frequency: 85 kHz (SAE J2954 compliant)  

---

## 🧪 Technologies Used

- **MATLAB/Simulink**  
- **LTSPICE** (for circuit analysis)  
- Compensation topology: **Series-Series (SS)**  
- Power Electronics: **MOSFET-based inverters**, **PWM control**

---

## 📈 Simulation Outputs

- Input voltage and current waveforms  
- Output battery voltage, charging current, and real-time SOC tracking  
- Efficiency plots and misalignment tolerance graphs  

---

## 🚀 Future Enhancements

- Integration with **Smart Grids and V2X** communication  
- Adaptive **coil reconfiguration** for improved alignment  
- Adoption of **SiC/GaN** wide-bandgap semiconductors  
- Lidar-assisted **autonomous coil alignment**  
- **Blockchain-based micropayments** for real-time EV charging  

---

## 👨‍💻 Team Members

- Jas Prajapati  
- Neel Shah  
- Urvesh Shah  
- Tejas Soni  

Project supervised by **Dr. Caniggia Viana**  
**University of Windsor – ELEC8900: EV Power Conversion**

---

## 📚 References

Key references used in this project are cited in the full documentation, including research papers from:
- IEEE Xplore  
- ScienceDirect  
- World Electric Vehicle Journal  
- Transportation Research Journals

---
