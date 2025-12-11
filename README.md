# EEE 491: IoT-Based Smart Socket (Home Energy Management) Project

This repository contains all code and simulation files developed for the 'IoT-Based Smart Socket' project as part of the EEE 491 Engineering Design I course.

**Project Goal:** To accurately measure the instantaneous power consumption of household appliances and guide the user toward energy savings through automated optimization based on a 3-tariff time-of-use schedule.

## ⚙️ Requirements and Solutions

| Requirement | Target Value | Proof File |
| :--- | :--- | :--- |
| **Measurement Error** | $\le \pm 2\%$ | `HLW8012_Accuracy_Calibration.m` |
| **Energy Savings** | $\ge 10\%$ | `Energy_Savings_Proof.m` |
| **Main Control Unit** | ESP32 | `[Insert ESP32 Main Code File Name Here]` |

## 📁 MATLAB Simulation Files

This folder contains the two core simulation files used to prove that the engineering requirements presented in the Design Report have been met.

### 1. HLW8012_Accuracy_Calibration.m
* **Purpose:** To verify the performance of the HLW8012 measurement module and apply the Least Squares linear calibration method to prove that the measurement error remains **below 2%**.

### 2. Energy_Savings_Proof.m
* **Purpose:** To mathematically demonstrate that the project's key marketing requirement of **10% or more** energy savings is achieved through the 3-tariff (Peak, Normal, Cheap) management strategy.

## 🔗 Communication

* **Mobile App / Dashboard:** MQTT Communication
* **Teamwork Management:** Trello
* **Design Report:** (Link/Location of the Report File)
