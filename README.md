# Smart Plant Tower

## Overview
The **Smart Plant Tower** is a solar-powered, vertically oriented indoor gardening system developed as a capstone thesis entitled **“Solar-Powered Vertical Garden: A Smart Plant Tower for Sustainable Indoor Gardening.”** The project addresses the limitations of traditional indoor planting in urban environments by integrating automation, sensor-based monitoring, and renewable energy to create a controlled microenvironment for plant growth.

The system combines an ESP32 microcontroller, environmental and nutrient sensors, automated irrigation, UV grow lighting, and a mobile application to deliver an efficient, space-saving, and user-friendly solution for modern indoor gardening. Prototype testing using lettuce demonstrated rapid and healthy growth from germination to the seedling stage within approximately 11 days, validating the effectiveness of the system as a plant-growth incubator.

This repository and system are provided strictly for **academic demonstration, evaluation, and research purposes** in relation to the approved capstone paper.

---

## Instructions for Use
This system is intended **only** for academic purposes as part of the approved capstone research:

- Demonstration during proposal, defense, or final evaluation
- Code and design inspection by advisers and panelists
- Local deployment for testing and validation

---

## Authorized Use
The following uses are **explicitly permitted**:

- System execution for academic evaluation and grading
- Review of source code, schematics, and documentation
- Hardware and software testing in a controlled academic setting

The intended users include:

- Capstone advisers
- Thesis panelists
- Authorized academic evaluators

---

## Restrictions
The following actions are **strictly prohibited** without written consent from the authors:

- Reuse or integration of any part of the system or source code into other projects
- Redistribution of the software, hardware designs, or documentation
- Modification and redeployment for institutional, instructional, or commercial use
- Claiming authorship or partial ownership of the system or its components

Any use beyond academic evaluation constitutes **unauthorized use** and may result in academic, institutional, or legal consequences.

---

## System Architecture

### Hardware Components
- ESP32 microcontroller (Wi-Fi & Bluetooth enabled)
- Soil moisture sensors (per pot)
- pH sensor and EC sensor for nutrient monitoring
- Ultrasonic sensor for water-level detection
- BME280 temperature and humidity sensor
- UV grow lights
- Water pump and solenoid valves
- Solar panel, MPPT charge controller, and 12V battery
- Power supplies, relays, inverter, and safety circuit breakers

### Software Components
- ESP32 firmware (Arduino-based)
- Mobile application (Android / iOS) built using React Native
- Firebase for authentication, real-time data sync, and storage

---

## Installation

### Prerequisites
**Hardware**
- Complete Smart Plant Tower assembly (as specified in the thesis)
- Stable Wi-Fi connection

**Software**
- Arduino IDE
- ESP32 board support package
- Firebase project configuration
- Android or iOS device for the mobile app

### Installation Steps
1. Assemble the Smart Plant Tower hardware according to the system schematics and prototype design.
2. Install Arduino IDE and configure ESP32 board support.
3. Upload the ESP32 firmware to the microcontroller.
4. Configure Firebase credentials in the firmware and mobile application.
5. Install the mobile application on an Android or iOS device.
6. Power the system using solar energy or AC fallback through the transfer switch.

---

## Usage

1. Power on the Smart Plant Tower.
2. Connect the ESP32 to Wi-Fi.
3. Launch the mobile application and log in.
4. Monitor real-time environmental data:
   - Temperature and humidity
   - Soil moisture
   - pH and EC levels
   - Water tank level
5. Control irrigation and lighting manually or allow automated operation.

The system automatically regulates watering and lighting based on sensor thresholds to maintain optimal plant conditions.

---

## Features

- **Automated Irrigation** using soil moisture sensing and solenoid valves
- **UV Grow Lighting Control** with manual and scheduled modes
- **Real-Time Monitoring** of temperature, humidity, pH, EC, and water level
- **Solar-Powered Operation** with battery storage and power fallback
- **Mobile Application Access** for remote monitoring and control
- **Vertical, Space-Efficient Design** suitable for indoor environments
- **Energy-Efficient and Sustainable Architecture**

---

## Related Research Paper

This system is the implementation of the approved capstone thesis:

**Title:** *Solar-Powered Vertical Garden: A Smart Plant Tower for Sustainable Indoor Gardening*  
**Degree:** Bachelor of Science in Computer Engineering  
**Institution:** STI College Novaliches  
**Date:** December 2025

All system designs, features, and evaluations are derived from and documented in the official manuscript.

---

## Authors and Credits

This project was developed as a capstone thesis by:

- **Joselito Vincent Ayong Borines Jr. (Lead Programmer)**
- **Gilan Clyde Esrella Dela Cruz (Quality Assurance)**
- **Vince Nixon Toquero Ilagan (Project Manager)**
- **Mark RJ Delao Plamiano (System Analyst)**

**Thesis Adviser:** Mark Alvin C. Malenab  
**Program:** Bachelor of Science in Computer Engineering

---

## Ownership, Rights, and Legal Notice

This project, including all software, hardware designs, documentation, and related materials, is the **original intellectual property of the authors**.

© 2025 Smart Plant Tower Research Team. All rights reserved.

Unauthorized reproduction, modification, redistribution, or use of this system beyond academic evaluation and grading violates intellectual property rights and academic integrity policies and may result in institutional disciplinary action and/or legal consequences.

Access to this repository does **not** grant ownership, authorship, or usage rights beyond those explicitly stated above.


