# ⚡ Star Dance - Custom 3D Printed Bench Power Supply

A reliable, non-microcontroller-based adjustable bench power supply featuring dual-channel current/voltage monitoring and an independent battery-powered cooling system, custom-designed from scratch for the Hack Club Star Dance challenge.

---

## 📋 Table of Contents
1. [Overview](#-overview)
2. [Key Features](#-key-features)
3. [Bill of Materials & Components](#-bill-of-materials--components)
4. [Circuit Architecture & Wiring](#-circuit-architecture--wiring)
5. [3D Design & Enclosure Integration](#-3d-design--enclosure-integration)
6. [Step-by-Step Assembly Guide](#-step-by-step-assembly-guide)
7. [AI Use](#-ai-use)
8. [License](#-license)
9. [Contributing](#-contributing)

---

## 🌟 Overview
The **Star Dance Power Supply** is a robust, desktop-class bench power supply built to provide stable, adjustable DC voltage and current for various electronics and maker projects. Unlike standard digital power supplies controlled by complex microcontrollers, this build relies on proven hardware regulation modules combined with a custom-engineered, modular 3D-printed enclosure designed in Autodesk Fusion 360.

---

## ⚙️ Key Features
* **Adjustable Output:** Smooth voltage and current regulation via a high-efficiency step-down converter.
* **Dual-Channel Monitoring:** Real-time visual feedback of both output voltage and current draw via an integrated digital display panel (DSN-VC288).
* **Independent Thermal Management:** An active cooling system powered by an independent 18650 Li-ion battery circuit to ensure continuous airflow without drawing noise or load fluctuations from the main power rail.
* **Modular Enclosure:** A split-body 3D-printed case designed for easy assembly, secure component housing, and clean cable management.

---

## 🛠️ Bill of Materials & Components
| Component | Description / Spec | Purpose |
| :--- | :--- | :--- |
| **Input Power Source** | ASUS Adapter (19V, 3.42A) | Main power input for the system |
| **Step-Down Regulator** | XL4015 DC-DC Buck Converter | Provides adjustable CV/CC power output |
| **Voltage/Current Meter** | DSN-VC288 Dual LED Panel | Displays real-time voltage and current metrics |
| **Cooling Fan** | Standard DC Fan | Dissipates heat from internal components |
| **Fan Power Circuit** | 18650 Li-ion Cell + TP4056 Module | Independent power source and safe charging for the fan |
| **Control Switches** | Rocker Switches (ON/OFF) | Power isolation and fan control |
| **Enclosure** | Custom PLA 3D Print (Split Design) | Structural housing for all internal electronics |

---

## 🔌 Circuit Architecture & Wiring
1. **Main Power Rail:** The 19V adapter input connects directly to the input terminals of the XL4015 buck converter. The output passes through the front-facing voltage/current shunt wiring to the binding posts.
2. **Display Integration:** The DSN-VC288 meter is wired into the output path to accurately measure and display voltage levels and current draw simultaneously.
3. **Cooling Subsystem:** To prevent electrical noise feedback into the main circuit, the cooling fan operates on an isolated line powered by an 18650 battery, managed via a TP4056 charging module and controlled by a dedicated rocker switch on the front panel.

---

## 📐 3D Design & Enclosure Integration
* **Software Used:** Autodesk Fusion 360
* **Design Strategy:** The enclosure was modeled as a modular two-part assembly to simplify printing, allow easy wiring access, and accommodate front panel cutouts for the DSN-VC288 display, potentiometers, and toggle switches.
* **Slicing & Printing:** Printed using high-quality PLA filament on a Bambu Lab printer with optimized wall generators, strong infill densities for structural rigidity, and clean support configurations.

---

## 🔧 Step-by-Step Assembly Guide
1. **Enclosure Fabrication:** 3D print the upper and lower case halves, ensuring smooth mating surfaces and clearing any support materials from ventilation slots.
2. **Component Mounting:** Secure the DSN-VC288 display, rocker switches, and potentiometers into their designated front-panel slots.
3. **Wiring & Soldering:** Solder the input/output connections to the XL4015 module, integrate the voltmeter shunts, and wire the independent battery-powered fan circuit.
4. **Integration & Closing:** Carefully guide all internal wiring into the enclosure to prevent pinching, align the modular case halves, and secure the final assembly.

---

## 🤖 AI Use
## 🤖 AI Use
AI tools were used minimally for formatting assistance and documentation structure. All design, engineering, and assembly work was done by me.

---

## 📜 License
This project is open-source and available under the [MIT License](LICENSE). 

---

## 🤝 Contributing
Contributions, bug reports, and feature suggestions are welcome! Feel free to open an issue or submit a pull request if you want to improve the enclosure design or circuit efficiency.