---
layout: default
title: Projects
permalink: /projects/
---

# Key Projects

Here is a selection of significant technical projects I have developed, ranging from safety-critical automotive systems to low-power IoT devices.

---

## 🔐 Secure Bootloader & Firmware Update
**Context:** *Neovigie Project (ICOM France)*  
**Tech Stack:** Cortex M4, AES-128, Python, FreeRTOS

Designed and implemented a secure bootloader solution from scratch for a radio equipment device.
*   **Security:** Implemented **AES-128 symmetric encryption** for firmware protection and signature verification to prevent tampering.
*   **Optimization:** Optimized the **Xmodem protocol** to minimize flash writing times and ensure data alignment.
*   **Tooling:** Developed custom **Python scripts** to handle binary manipulation, encryption, and installation on external SPI Flash.
*   **Testing:** Created a test suite covering internal/external memory corruption scenarios.

---

## 📡 IoT "Sensory Integration" for Heavy Machinery
**Context:** *Titan Europe Group (Italtractor ITM)*  
**Tech Stack:** Nordic nRF51 (ARM Cortex-M0), BLE 4.1, Accelerometers

Developed prototypes for low-power IoT sensors applied to mining machinery (e.g., Hitachi ex5500).
*   **Sensing:** Implemented algorithms to monitor **temperature and wear** of mechanical parts.
*   **Vibration Analysis:** Integrated calibrated accelerometers to detect anomalies in roller oil chambers.
*   **Connectivity:** Realized a **Bluetooth-to-GSM Gateway** for remote data transmission.
*   **Hardware:** Validated prototypes using oscilloscopes and current probes to ensure low-power consumption.

---

## 🔌 Custom Hardware for PSM Machines
**Context:** *Indaco Project*  
**Tech Stack:** PCB Design, Embedded C, SMD Soldering

Full-stack electronics development for industrial automation.
*   **Design:** Designed proprietary **PCB circuits** tailored to specific machine requirements.
*   **Prototyping:** Managed the entire lifecycle from component selection to **hand-soldering SMD components** and final testing.
*   **Firmware:** Developed the embedded software to control the new proprietary electronics.

---

## 🚗 Automotive Bootloader & Diagnostics
**Context:** *Marelli*  
**Tech Stack:** UDS, CAN-FD, XCP, Vector Suite

Implementation of bootloader solutions for the automotive sector.
*   Configured **UDS services** on CAN-FD and implemented **XCP protocols**.
*   Developed complex drivers for **ASIL D** safety compliance.
*   Managed the data exchange interface between the Application Software (ASW) and the Bootloader.

---

[🔙 Back to Home](/)
