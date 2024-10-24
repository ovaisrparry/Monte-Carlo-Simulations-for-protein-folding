# Protein Unfolding Simulation Using Monte Carlo Methods

## Overview

This project simulates the **unfolding of a protein** on a lattice using **Monte Carlo methods**. The simulation models a 2D lattice where protein segments occupy certain positions. The energy of the system is calculated based on interactions with neighboring segments, and the Monte Carlo approach is used to attempt movements and accept or reject them based on energy changes.

### Features:
- **Lattice-based Model**: Protein segments are placed on a 2D grid, simulating folding and unfolding.
- **Monte Carlo Algorithm**: Used to simulate protein dynamics with energy minimization techniques.
- **Energy Calculation**: Based on nearest-neighbor interactions and the Boltzmann distribution.

## Contents

- **Lattice Setup**: Initialize a 2D lattice with protein segments.
- **Monte Carlo Simulation**: Perform random movements of protein segments and compute energy changes.
- **Energy Calculation**: Calculate system energy based on neighboring interactions.
- **Simulation Output**: Display the final energy after the simulation steps.

## Requirements

To run the notebook, you need the following libraries:

- `numpy`

Install it using pip:

```bash
pip install numpy
