# LiRebooterV1.1

> Ultra-miniature 1S Li-Ion battery monitoring and power management board with 10-hour cyclic reboot, under-voltage cutoff, and 5A continuous output capability.

<div align="center">

[![Battery](https://img.shields.io/badge/BATTERY-1S%20LI--ION-cf222e?style=for-the-badge&logo=circuitverse&logoColor=white)](#)
[![Max Current](https://img.shields.io/badge/CURRENT-5.0A%20MAX-0969da?style=for-the-badge)](#)
[![Under-Voltage Cutoff](https://img.shields.io/badge/CUTOFF-3.5V-d29922?style=for-the-badge)](#)
[![Auto Recovery](https://img.shields.io/badge/RECOVERY-3.9V-2da44e?style=for-the-badge)](#)
[![Reboot](https://img.shields.io/badge/REBOOT-10h%20CYCLIC-6f42c1?style=for-the-badge)](#)
[![Dimensions](https://img.shields.io/badge/DIMENSIONS-9.8%20%C3%97%206.3%20mm-57606a?style=for-the-badge)](#)

</div>

<p align="center">
  <img src="LiRebooterV1.1_3D.png" alt="LiRebooterV1.1 3D Render" width="48%">
  <img src="LiRebooterV1.1_DIM.png" alt="LiRebooterV1.1 Dimensions" width="48%">
</p>

---

### ⚡ Electrical Specifications & Battery Protection

* **🔋 Target Battery Architecture**:
  * Designed for **1S Li-Ion / Li-Po** battery cells.
  * **Output Voltage**: Direct battery voltage pass-through to load.
* **⚡ Continuous Load Capacity**:
  * **Maximum Continuous Current**: Up to **5.0 A**.
* **🛡️ Under-Voltage Discharge Protection**:
  * **Cutoff Voltage**: Output disconnects automatically when battery voltage falls below **3.5 V** to prevent over-discharge and cell degradation.
  * **Hysteresis Auto-Recovery**: Operation resumes automatically once battery voltage recovers to **3.9 V** (upon recharging).
* **📏 Form Factor**:
  * Ultra-compact miniature footprint measuring **`9.8 × 6.3 mm`**.

---

### ⚙️ Operating Logic & Timers

* **Startup Delay**:
  * **10-Second Delay**: Power stabilization delay on initial power-on before enabling load output.
* **Autonomous 10-Hour Cyclic Reboot**:
  * Automatically power-cycles the connected load every **10 hours** to clear potential device freezes and preserve system autonomy.