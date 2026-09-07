# LISv1

> Intelligent Wide-Input (5.35–36V) to 5V/3A Power Switching Module with Precision MEMS Micro-Motion & Vibration Detection.

<div align="center">

[![Sensor](https://img.shields.io/badge/SENSOR-MEMS%20MICRO--MOTION-cf222e?style=for-the-badge&logo=circuitverse&logoColor=white)](#)
[![Input Voltage](https://img.shields.io/badge/INPUT-5.35~36%20VDC-0969da?style=for-the-badge)](#)
[![Output](https://img.shields.io/badge/OUTPUT-5.0V%203.0A-2da44e?style=for-the-badge)](#)
[![Topology](https://img.shields.io/badge/CONVERTER-SYN531R%20SYNC%20BUCK-6f42c1?style=for-the-badge)](#)
[![Dimensions](https://img.shields.io/badge/DIMENSIONS-35.6%20%C3%97%2017.2%20mm-57606a?style=for-the-badge)](#)

</div>

<p align="center">
  <img src="LISv1_3D.png" alt="LISv1 3D Render" width="48%">
  <img src="LISv1_DIM.png" alt="LISv1 Dimensions" width="48%">
</p>

---

### ⚡ Electrical Specifications & Power Features

* **🔌 Wide Input Voltage Range (`VIN`)**:
  * **Operational Supply Window**: **5.35 VDC to 36.0 VDC**.
* **⚡ Regulated Switched Output (`5V`)**:
  * **Output Voltage**: Stabilized **5.0 VDC**.
  * **Continuous Load Current**: Up to **2.8 A**.
* **📳 Integrated Micro-Motion & Vibration Detection**:
  * 3-axis MEMS accelerometer detects micro-movements and wakes up the main MCU for processing.
* **🧠 Intelligent Controller**:
  * Onboard MCU executes smart signal filtering to prevent false triggers and manages hold-on timers.
* **📏 Form Factor**:
  * Compact notched PCB measuring **`35.6 × 17.2 mm`**.

---


### ⚙️ Operating Logic & Typical Applications

* **Automated Wake-On-Motion**:
  * While stationary, the board remains in a low-power sensing state.
  * Upon detecting micro-movement or physical vibration, the synchronous converter energizes the 5.0V load output.
* **Programmable Run Timer**:
  * Keeps the load energized for a calibrated hold time after movement ceases, ensuring continuous operation during temporary pauses.

