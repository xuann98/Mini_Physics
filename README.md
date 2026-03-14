# Mini_Physics
Just for fun 

This is a simple Python simulation of the N-body problem, demonstrating gravitational interactions between multiple celestial bodies. 

The project is implemented in a **Jupyter Notebook** since it is often used in physics and to familiarize myself with it for the upcoming semester.

## Features

- Simulates gravitational interactions using Newton's law of gravitation.
- Supports multiple bodies (Sun, Earth, Mars, etc.).
- Implements simple **Euler integration** to update positions and velocities.
- Visualizes orbits with **Matplotlib**, including orbit trails and final positions.
- Fully interactive in **Jupyter Notebook**, allowing parameter changes and experimentation.

## Getting Started

### Requirements
- Python 3
- NumPy
- SciPy
- Matplotlib
- Jupyter Notebook or JupyterLab

## Usage

- Modify body parameters (mass, position, velocity) in the notebook to test out different scenarios.
- Adjust `dt` and `steps` to change simulation time and resolution.
- Run the notebook cells sequentially to compute forces, update positions, and visualize orbits.

## Future Improvements

- Implement higher-order integration methods (e.g., Runge-Kutta, Velocity Verlet) for more accurate orbits.
- Add real-time animation of bodies moving.
- Include user input to add/remove bodies dynamically.
- Extend to 3D simulations.