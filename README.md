# Quantum-Heisenberg-Simulation
Numerical simulation of spin dynamics in hexagonal lattices using Python and Qiskit.
# Quantum Dynamics: Heisenberg Model Simulation
This project implements a classical and quantum-inspired simulation of spin dynamics on a hexagonal lattice.

## 🚀 Key Features
- **Lattice Modeling:** Hexagonal topology generated via NetworkX.
- **Exact Simulation:** Time evolution using SciPy's matrix exponentiation.
- **Quantum-Ready:** Built-in Trotterization logic using Qiskit.
- **Data Visualization:** Probability distribution plots for spin states.

## 📊 Sample Results
![Simulation Plot](visualizations/Lattice.png)

*figure 1: lattice configeration*
![Simulation Plot](visualizations/Exact.png)
*figure 2: Probability of spin-down occupation over time.*
*analysis: By observing the wave behavior in figure 2 we can extrapolate the site’s spin state at a given time. when t=0, 3.25 and 6 (1∕J) the probability of a spin down is 100% in contrast when the probability is 0% that means that the site is in a spin up state ,furthermore the intervals between 0% and 100% exist in a superposition of |1⟩ and |0⟩.*
## 🛠️ Tech Stack
- **Language:** Python 3.x
- **Libraries:** NumPy, SciPy, Qiskit, Matplotlib, NetworkX
