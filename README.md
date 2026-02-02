# Stochastic Differential Equations Simulator

## Overview

This project was completed during MIT's IAP class 6.S184: Generative AI with Stochastic Differential Equations and provides an interactive exploration of stochastic processes through implementations of classical numerical integration schemes. It demonstrates how randomness influences dynamical systems and includes visualizations of Brownian motion, Ornstein-Uhlenbeck processes, and Langevin dynamics.

## Key Features

- **Numerical Integration Schemes**
  - Euler method for ODEs
  - Euler-Maruyama method for SDEs

- **Implemented Stochastic Processes**
  - Brownian Motion with configurable diffusion
  - Ornstein-Uhlenbeck (OU) processes with mean reversion
  - Langevin dynamics for distribution transformation

- **Visualization Tools**
  - Trajectory plots with distribution histograms
  - 2D density visualization for distribution evolution
  - Interactive parameter exploration
  - Side-by-side comparison of different configurations

- **Mathematical Insights**
  - Connection between OU processes and Langevin dynamics
  - Stationary distribution analysis
  - Score-based modeling fundamentals

## Installation

1. Clone the repository:
```bash
git clone https://github.com/SeekingBeta314/sde-simulator.git
cd sde-simulator
```

2. Create and activate a virtual environment:
```bash
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install required packages:
```bash
pip install -r requirements.txt
```

4. Launch Jupyter Notebook:
```bash
jupyter notebook "Lab One.ipynb"
```
