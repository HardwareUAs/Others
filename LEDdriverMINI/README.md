# LEDdriverMINI

> Ultra-compact 4.5–25V Step-Down (Buck) Constant-Current LED Driver (10–400 mA) for low-power LED illumination, IR backlights, and camera indicators.

<div align="center">

[![Driver Type](https://img.shields.io/badge/TYPE-CONSTANT%20CURRENT-cf222e?style=for-the-badge&logo=circuitverse&logoColor=white)](#)
[![Input Voltage](https://img.shields.io/badge/INPUT-4.5~25%20VDC-0969da?style=for-the-badge)](#)
[![Output Current](https://img.shields.io/badge/CURRENT-10~400%20mA-2da44e?style=for-the-badge)](#)
[![Topology](https://img.shields.io/badge/TOPOLOGY-STEP--DOWN%20BUCK-6f42c1?style=for-the-badge)](#)
[![Dimensions](https://img.shields.io/badge/DIMENSIONS-14.9%20%C3%97%2011.5%20mm-57606a?style=for-the-badge)](#)

</div>

<p align="center">
  <img src="LEDdriverMINI_3D.png" alt="LEDdriverMINI 3D Render" width="48%">
  <img src="LEDdriverMINI_DIM.png" alt="LEDdriverMINI Dimensions" width="48%">
</p>

---

### ⚡ Electrical Specifications & Power Features

* **🔋 Operating Input Voltage (`VIN`)**:
  * **Full Regulation Range**: **4.5 VDC to 25.0 VDC**.
* **〰️ Constant Output Current**:
  * **Configurable Range**: Fixed output current from **10 mA to 400 mA** (set via onboard precision resistors R1 / R2).
* **🎯 Target Applications**:
  * Low-power LED lighting, camera IR illuminators, machine vision backlights, and portable equipment indicators.
* **📏 Dimensions**:
  * Ultra-compact board size of **`14.9 × 11.5 mm`** .

---

### ⚙️ Operating Guidelines

* **Buck Voltage Headroom**: As a step-down (buck) topology, the input supply voltage must be higher than the total forward voltage ($V_f$) of the connected LED load.
* **Current Programming**: Current is precisely governed by the onboard shunt resistors R1 and R2.