# BHE 3x3 HT Pressure-Driven Flow

This folder contains a Python script for generating OGS input files for a 3D heat transport simulation with a 3×3 BHE array.

## Description
The script automatically generates:
- `model_mesh.vtu`
- `heater_mesh.vtu`
- `model_geo.gml`
- `simulation_plume.prj`

## Model Features
- 3D bulk mesh generation
- heater submesh extraction
- pressure-driven groundwater flow
- volumetric heat source applied to heater submesh
- OGS HT project file generation

## Requirements
```bash
pip install -r requirements.txt
