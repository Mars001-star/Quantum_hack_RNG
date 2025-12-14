# Battery & Wind Farm Optimization

This repository contains Python implementations for analyzing, optimizing, and simulating the operation of a battery system coupled with a wind farm. The project includes classical optimization as well as quantum-inspired solutions using QAOA.

---

## 📂 Project Structure

- `data_plot.ipynb`  
  Visualization of wind power and electricity price data from `input_data.csv`.

- `classical_opt.ipynb`  
  Classical stochastic optimization model using linear programming (PuLP) to determine battery charging/discharging schedules under multiple wind scenarios.

- `quantum_opt.ipynb`  
  Quantum-inspired optimization using QAOA on a 12-qubit QUBO formulation to determine battery operation schedules.

- `input_data.csv`  
  Input dataset containing:
  - Hour (`hour`)
  - Wind scenarios (`scenario_1`, `scenario_2`, ..., `scenario_13`)
  - Electricity price (`price`)

---

## ⚡ Dependencies

Make sure to install the required Python packages:

```bash
pip install pandas numpy matplotlib pulp
