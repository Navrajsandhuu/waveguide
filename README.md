# TEₘₙ Mode Visualization in Rectangular Waveguides

This project is an interactive 3D visualization tool for exploring **transverse electric (TEₘₙ) modes** in rectangular waveguides using **Python**, **Plotly**, and **Jupyter Notebook**.

It simulates the electric field magnitude inside a waveguide and renders the field distribution in 3D using a realistic, FEM-style block visualization with a true-to-scale rectangular prism geometry.



## Features

- Adjustable sliders for mode indices `m` and `n` (TEₘₙ modes)
- Real-time 3D electric field magnitude visualization
- True geometric scaling (e.g., 1.0 × 0.5 × 5.0 waveguide at 10 GHz)
- Rotatable, zoomable, and interactive view using Plotly
- Continuous block-style field rendering (no gaps between voxels)



## Getting Started

### Requirements

- Python 3.7+
- Jupyter Notebook
- ipywidgets
- numpy
- plotly

### Installation

```bash
pip install numpy plotly ipywidgets
jupyter nbextension enable --py widgetsnbextension --sys-prefix
