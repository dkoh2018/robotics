# Double Pendulum Simulation with Torques

This repository contains a **double pendulum simulation** using the **Euler-Lagrange method** for deriving equations of motion and **numerical integration** with `odeint`. It includes visualizations of **joint angles over time**.

- Uses **SymPy** to derive **Euler-Lagrange equations**.
- Numerically solves the system using **Scipy’s `odeint`**.
- Plots **joint angles over time** for analysis.
- Allows **custom torque inputs** for controlled motion.

## 🛠 Technologies Used
- **Python** (SymPy, NumPy, SciPy)
- **Matplotlib** (for visualization)

## 🚀 Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/dkoh2018/double_pendulum_simulation.git
cd double_pendulum_simulation
pip install -r requirements.txt
```

## ▶️ Usage
Run the simulation:
```bash
python simulation.py
```
Modify the torque functions inside `simulation.py` to experiment with different controls.

## 📊 Example Output
The simulation generates plots showing how the **joint angles** evolve over time.
