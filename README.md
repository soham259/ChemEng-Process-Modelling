# Modelling Lid-Driven Cavity Flow

## Overview
This project focuses on the numerical simulation of **2D incompressible lid-driven cavity flow**, a classical benchmark problem in Computational Fluid Dynamics (CFD). Simulations were carried out using **OpenFOAM** and a **custom Python-based solver**.

## Objectives
- Simulate lid-driven cavity flow at different Reynolds numbers
- Implement multiple numerical methods for comparison
- Validate numerical results with benchmark data

## Methodology
- **OpenFOAM**: Finite Volume Method using icoFoam and pimpleFoam
- **Python Solver**:
  - Finite Difference Method (streamfunction–vorticity formulation)
  - Lattice Boltzmann Method (D2Q9-BGK)
- Reynolds numbers studied: Re = 100, 1000, 5000

## Key Features
- Grid independence and parameter sensitivity analysis
- Comparison with benchmark data (Ghia et al.)
- Visualization of velocity, vorticity, pressure, and streamlines

## Tools & Technologies
- OpenFOAM
- Python (NumPy, Matplotlib)
- ParaView

## Learning Outcomes
- Understanding of CFD fundamentals
- Experience with numerical solvers
- Hands-on exposure to open-source CFD tools
