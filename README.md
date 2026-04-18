# Autonomous Parking and Reverse using Reinforcement Learning 🚗🅿️

This repository contains the code, simulation framework, and evaluation results for the research paper:

**SmartGridDrive: Adaptive Q-Learning Framework for Precision Self-Parking and Reverse Navigation in Dynamic Autonomous Systems"**

 

## 🔍 Overview

This project presents a modified Q-learning method combined with RRT and MPC to enable autonomous vehicles to perform precise parking and reversing maneuvers in dynamic grid environments.

### Core Features
- Modified tabular Q-learning with:
  - ✅ Adaptive exploration
  - ✅ Lookahead obstacle prediction
  - ✅ Priority-based updates
- Hybrid architecture with:
  - 🧭 RRT for path planning
  - 🧠 MPC for smooth trajectory tracking
- Simulation of dynamic 2D grid with obstacles and moving targets

## 📁 Directory Structure

- `simulation/` – Core modules (grid, Q-learning, RRT, MPC)
- `notebooks/` – Jupyter notebook demo
- `results/` – Sample outputs, plots, and logs
- `run_simulation.py` – Main runner script

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- Install dependencies:
```bash
pip install -r requirements.txt
```

### Running the simulation
```bash
python run_simulation.py
```

## 📊 Sample Results

- Success Rate: 92.4%
- Average Steps: 38.2
- Collision Rate: 1.8%
- Alignment Error: 6.7 cm

See `/results` folder for plots and output examples.

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

## 📬 Contact

**Revati Raman Dewangan**  
GitHub: [https://github.com/rev2004](https://github.com/rev2004)
