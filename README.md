# Project KERB: Simulated Reusable Rocket Design & Optimization  

**Author:** Arnav Gaddam(ArnavKSP)
 Independent Aerospace Research  
---

## Overview  
Project KERB (Kerbal Space Program) is an open-source student research project exploring **reusable launch vehicle efficiency** through simulation, physics modeling, and data analytics.  
Using **Kerbal Space Program (KSP)** for realistic flight simulation and **python** for quantitative analysis, the project investigates how stage ratios, thrust curves, and aerodynamic parameters affect total Δv and fuel efficiency as well as the simulator's validity in real-world applications.  

Goal: Bridge educational simulation and real-world aerospace modeling — proving that game-based environments can generate credible, reproducible engineering data.  

---

##  Research Objectives
1. Quantify performance differences between expendable vs reusable launch systems.  
2. Validate in-game physics against the Tsiolkovsky Rocket Equation and atmospheric drag models.  
3. Apply optimization algorithms (SciPy, NumPy) to minimize fuel usage and maximize payload fraction.  
4. Publish a reproducible dataset and Python toolkit for student aerospace research.

---

##  Methodology Pipeline
| Stage | Tool / Framework | Output |
|-------|------------------|---------|
| Flight Simulation | Kerbal Space Program | Telemetry logs (CSV) — altitude, velocity, thrust, fuel mass |
| Data Parsing & Cleaning | Python (pandas + NumPy) | Normalized datasets |
| Analysis & Modeling | SciPy optimization + custom Δv functions | Efficiency metrics, graphs |
| Visualization | Matplotlib / Plotly | Trajectory plots, Δv curves |
| Validation | MATLAB Aerospace Toolbox  | Cross-check with orbital mechanics equations |

---

##  Metrics Tracked
- Δv budget and losses  
- Thrust-to-Weight ratio (TWR)  
- Payload fraction (%)  
- Fuel mass flow rate  
- Stage efficiency comparison  
- Re-entry velocity and landing accuracy  

---

##  Repository Structure

Project-KERB/
├── data/ # Raw and processed flight CSV files
├── scripts/ # Python analysis and Δv calculation modules
├── notebooks/ # Jupyter notebooks for graphs and experiments
├── figures/ # Plots and visual outputs
├── docs/ # Research paper, metrics definitions, references
└── README.md # Project overview


Future Work

Cross-simulate missions in STK (Systems Tool Kit) for orbital accuracy comparison.

Release Fusion Aerospace Student Toolkit for peer schools.

References

NASA Basics of Space Flight – Jet Propulsion Laboratory

Tsiolkovsky Rocket Equation (1903)

“Reusable Launch Vehicle Concepts” – AIAA Paper 2021-3724

Kerbal Space Program Documentation

