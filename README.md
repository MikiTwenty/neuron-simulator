# Neuron Simulator

Interactive simulator for the Morris-Lecar neuron model.

## Description

This project provides an interactive simulation and visualization of the membrane potential and gating variable evolution in a neuron, using the Morris-Lecar model. It includes tools for critical point analysis and interactive plotting, with customizable external current and other parameters.

## Features

- **ODE Simulation**: Numerical solution of the Morris-Lecar model differential equations.
- **Visualization**: Interactive plots for membrane potential, recovery variable, and phase plane.
- **Analysis**: Automatic detection of critical (crossing) points between potential and gating variable.
- **Interactive Widgets**: Real-time parameter adjustment via sliders and buttons.
- **Plot Saving**: Export results as PNG images.

## Requirements

- Python 3.10+
- See `requirements.txt` for the full list of dependencies.

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/MikiTwenty/neuron-simulator.git
   cd neuron-simulator
   ```

2. Install dependencies:

   ```sh
   pip install -r requirements.txt
   ```

## Usage

1. Start Jupyter Notebook:

   ```sh
   jupyter notebook
   ```

2. Open `main.ipynb` and follow the instructions cell by cell.
3. Use the sliders to change the external current and observe the changes in the plots.

## Project Structure

- `main.ipynb` — Main notebook with code, explanations, and visualizations.
- `requirements.txt` — Python dependencies.
- `images/` — Folder for generated plots.
- `README.md` — This file.

## Credits

- **Author**: Michele Ventimiglia

## License

See the `LICENSE` file for details.
