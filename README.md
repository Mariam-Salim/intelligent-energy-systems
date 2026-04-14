# Intelligent Energy Systems

A portfolio of applied electrical engineering projects focused on energy systems, HVAC optimisation, and intelligent control using data-driven methods.

---

## Core Skills Demonstrated

- Energy system modelling (EnergyPlus)
- Control strategy development (rule-based and reinforcement learning)
- Python for engineering analysis (NumPy, Pandas, Matplotlib)
- Time-series data processing
- Performance evaluation (energy, comfort, emissions)
- Simulation-based optimisation

---

## Projects

### 1. HVAC Control Optimisation (RL vs Baseline)

**Goal:** Improve HVAC efficiency while maintaining thermal comfort.

- Developed a simulation-based control environment using EnergyPlus  
- Implemented reinforcement learning controller (PPO)  
- Compared against baseline rule-based control  
- Evaluated:
  - Energy consumption  
  - Comfort violations  
  - Control stability  

**Outcome:** Demonstrated trade-off between comfort and energy savings under dynamic occupancy.

---

### 2. Energy & Emissions Analysis

**Goal:** Analyse building energy use and associated emissions.

- Processed time-series energy data  
- Integrated grid emissions intensity data via API  
- Converted HVAC energy from Joules to kWh  
- Quantified emissions impact of control strategies  

**Outcome:** Showed how control decisions affect both energy use and carbon footprint.

---

### 3. Demand Response Simulation

**Goal:** Evaluate building response to dynamic energy pricing or grid signals.

- Simulated load shifting strategies  
- Analysed peak demand reduction  
- Assessed operational trade-offs  

**Outcome:** Demonstrated potential for grid-interactive efficient buildings.

---

## Example Outputs

- Zone temperature profiles vs setpoints  
- HVAC energy consumption trends  
- Comfort violation metrics  
- Emissions over time  

(See /docs/figures/ for visualisations)

---

## Tech Stack

- Python  
- EnergyPlus  
- Stable-Baselines3 (Reinforcement Learning)  
- Pandas / NumPy  
- Matplotlib  

---

## Project Motivation

Modern energy systems require intelligent, adaptive control strategies to balance:

- Energy efficiency  
- Occupant comfort  
- Environmental impact  

This repository explores how simulation and data-driven methods can support better engineering decisions in building systems.

---

## How to Run

```bash
git clone https://github.com/yourusername/intelligent-energy-systems.git
cd intelligent-energy-systems
pip install -r requirements.txt
```

Run individual projects from their respective folders.

---

## Author

Electrical Engineer with experience in:

- Systems modelling  
- Control and optimisation  
- Energy and HVAC simulation  
