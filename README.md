# Analog Volume Expander

**Real-time audio volume expander to enhance the dynamic range of audio signals.**

## 📖 Project Overview
This project involves the design and implementation of an **Analog Volume Expander**, which enhances the dynamic range of audio signals by applying upward expansion. It is tailored for applications like recording, broadcasting, and live sound systems.

### Key Features
- Real-time signal processing with minimal latency.
- User-configurable threshold and expansion ratio.
- Efficient **Control Voltage Processor** and **Voltage-Controlled Amplifier (VCA)**.
- Integrated notch filter to eliminate power line interference.
- Dual-layer PCB design and custom 3D-printed enclosure.

---

## 🛠 System Design
### Functional Block Diagram

<img src="images/screenshots/block%20diagram.png" width="800" height="auto" />

### Core Components
- **Control Voltage Processor**: Processes the input signal to generate control voltages.
- **Voltage-Controlled Amplifier (VCA)**: Adjusts the gain dynamically.
- **Notch Filter**: Removes power line noise (50Hz).
- **Power Supply**: Provides stable and isolated power to the system.


---

## 📸 Project Highlights
### PCB Design
- **2-layer PCB Design**: Designed using Altium Designer, manufactured via JLCPCB.
- **Key Features**:
  - Efficient layout with minimal wiring.
  - Proper power-signal separation for reliability.


<img src="images/screenshots/pcb_design.png" width="800" height="auto" />

### Enclosure Design
- **3D-printed enclosure**:
  - Designed in SolidWorks.
  - Printed using durable PLA+ material.
- **Dimensions**: 154 mm × 116 mm × 70 mm.

<div style="display: flex; justify-content: space-between;">
    <img src="images/screenshots/enclosure_design.jpg" alt="Image 1" width="40%" height="auto">
    <img src="images/PIctures/Screenshot 2024-12-16 212225.png" alt="Image 2" width="46%" height="auto">
</div>

---
![Solidworks](https://img.shields.io/badge/Solid_Works_-red)
![Altium](https://img.shields.io/badge/Altium_Designer_-%23A5915F?logo=altiumdesigner&logoColor=white)
![LTspice](https://img.shields.io/badge/LTspice-%230078D7?logo=analogdevices&logoColor=white)
