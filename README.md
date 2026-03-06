
# Battery SOC Estimation using 1RC and 2RC Equivalent Circuit Models

This repository implements State of Charge (SOC) estimation for lithium‑ion batteries using:

• 1RC Equivalent Circuit Model  
• 2RC Equivalent Circuit Model  
• Extended Kalman Filter (EKF)

The project is written in MATLAB and designed to be fully reproducible.

---

## What This Project Does

1. Loads battery data (time, current, voltage)
2. Estimates battery capacity
3. Computes SOC using Coulomb counting
4. Identifies Equivalent Circuit Model parameters
5. Builds OCV–SOC relationship
6. Runs EKF for SOC estimation
7. Compares 1RC vs 2RC model performance

---

## Repository Structure

BatteryProject
│
├── data/
│   └── DATA1.xlsx
│
├── src/
│   ├── run_1RC_model.m
│   ├── run_2RC_model.m
│   ├── cost1RC.m
│   ├── cost2RC.m
│   └── simulate2RC.m
│
├── scripts/
│   └── run_all_models.m
│
├── results/
│   └── generated plots
│
└── README.md

---

## Requirements

MATLAB (R2020+ recommended)
Optimization Toolbox

---

## How to Run

Clone the repository

https://github.com/AnshG14pro/BatteryProject

Open MATLAB and run:

run scripts/run_all_models.m

