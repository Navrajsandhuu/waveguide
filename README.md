# 3D Waveguide Mode Simulator (TEₘₙ / TMₘₙ)

This is an interactive simulator for visualizing electromagnetic field propagation in rectangular waveguides using Jupyter Notebook. The tool supports both TE and TM modes and provides real-time 3D visualizations alongside analytical plots of phase constant and effective refractive index.

---

## Features

- Supports TEₘₙ and TMₘₙ modes with adjustable mode indices `m`, `n`
- Interactive 3D visualization of electric or magnetic field magnitudes
- Real-time plots:
  - Phase constant βₘₙ vs frequency
  - Effective refractive index nₑff vs frequency
- Cutoff frequency detection and display
- Adjustable simulation parameters:
  - Frequency (GHz): 0.1 to 15.0  
  - Width `a` (m): 0.1 to 3.0  
  - Height `b` (m): 0.1 to 3.0  
  - Length `L` (m): 1.0 to 10.0  

---

## Requirements

- Python 3.8+
- Jupyter Notebook
- Packages:
  - numpy
  - plotly
  - ipywidgets

Install dependencies via:

```bash
pip install numpy plotly ipywidgets
