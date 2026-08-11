# 3D-Architected NASICON Solid-State Unit: Interfacial & Techno-Economic Optimization

---

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21567468.svg)](https://doi.org/10.5281/zenodo.21567468) ![Status](https://img.shields.io/badge/Status-Research_POC-orange) ![Type](https://img.shields.io/badge/Type-Simulation_Model-blue)

---

An open-source multiphysics modeling framework utilizing **PyBaMM** and a custom **Techno-Economic Analysis (TEA)** optimizer to design an ultra-low resistance, financially viable 3D solid-state sodium-ion battery interface.

## 🚀 Executive Summary
Standard 2D flat-plate ceramic solid-state interfaces suffer from low-temperature "thermal walls" and rapid space-charge degradation. This project introduces a **3D Zigzag Interface with Logarithmic Junction Grading** to dilute local current density, lowering Area-Specific Resistance (ASR) while maximizing factory profit margins.

### 📊 Key Performance Metrics Achieved:
* **Area-Specific Resistance ($ASR$):** Reduced by **67.6%** ($68.0 \Omega \cdot cm^2$ vs $210.0 \Omega \cdot cm^2$ baseline).
* **Critical Current Density ($CCD$):** Validated at **$2.6 \text{ mA/cm}^2$** ($3.25\times$ safety margin against dendrites).
* **Optimal Structural Complexity:** Identfied a geometric sweet spot of **$2.21\times$ Area Enhancement**, balancing cell performance with factory yields to maximize net annual profits.
* **Production Cost Vector:** Target cost optimized to **approx $74/kWh**, safely under the $110/kWh commercial target marker.

## 📁 Repository Structure
* `/models/01_pybamm_eis_simulation.ipynb`: Time-domain and Frequency-domain (EIS) electrochemical simulation code.
* `/models/02_techno_economic_optimizer.ipynb`: Parametric complexity vs. yield optimizer loop.

## 📈 Validated Simulation Frontier
| Nyquist Response Baseline vs 3D | Financial Optimization Sweet Spot |
|---|---|
| ![](/assets/nyquist_plot.png) | ![](/assets/optimization_frontier.png) |

## 🛠️ Installation & Usage
1. Clone the repository:
   ```bash
   git clone [https://github.com/Abhishek1033ubuntu/3D-NASICON-Optimization.git](https://github.com/Abhishek1033ubuntu/3D-NASICON-Optimization.git)
   Install dependencies:
   pip install -r requirements.txt

# Important Notice

This repository contains code published for demonstration and testing purposes only. 
The underlying intellectual property (IP) — including inventions, processes, methods, 
algorithms, and research results — is proprietary and protected under Indian law and 
international treaties (Berne Convention, Paris Convention, TRIPS Agreement).

By accessing this repository, you agree:
- The code may be viewed and studied for non-commercial, educational, or research use only.
- Any reproduction, modification, distribution, or commercialization of the IP is strictly prohibited.
- Enforcement of rights will be pursued under Indian jurisdiction and applicable international treaties.

For licensing inquiries or commercial permissions, please contact:
Abhishek Singh  | UIDAI: 9414 9122 9013
Email: abhishek1033@gmail.com | abhishek.s@live.in
Location: Madhya Pradesh, India
