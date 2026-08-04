# Python — Scientific Computing & CFD Data Analysis

[![Python](https://img.shields.io/badge/Python-Jupyter%20Notebook-orange)](https://jupyter.org)
[![Status](https://img.shields.io/badge/Status-Active-green)]()

> Python scripts and Jupyter notebooks for **scientific computing, numerical methods, and CFD post-processing**. Covers data extraction from OpenFOAM binary fields, matplotlib visualization, numpy/scipy numerical routines, and general Python programming exercises.

---

## Contents

| Folder / Notebook | Topic |
|:---|:---|
| `openfoam_postprocess/` | Binary field reader, scour depth extraction, alpha.a threshold tracking |
| `numerical_methods/` | Root finding, ODE solvers (RK4, Euler), FDM 1D/2D |
| `data_visualization/` | matplotlib: contour plots, time series, validation overlays |
| `general/` | Python fundamentals, string ops, file I/O, regex |

---

## Key Scripts

```python
# Extract scour depth from OpenFOAM binary alpha.a field
python openfoam_postprocess/extract_scour.py

# Plot SedFoam result vs. Mao (1986) experimental data
python data_visualization/plot_validation.py
```

---

## Dependencies

```bash
pip install numpy scipy matplotlib pandas jupyter
```

---

## Related CFD Projects

| Repo | Description |
|:---|:---|
| [2DPipelineScour](https://github.com/DKS-MANAGER/2DPipelineScour) | Pipeline scour OpenFOAM case |
| [bridge_sedfoam](https://github.com/DKS-MANAGER/bridge_sedfoam) | Bridge pier scour OpenFOAM case |

---

## Author

**Divyansh Kumar Singh (DKS)**  
M.Tech — Civil Engineering, IIT Kanpur  
[GitHub](https://github.com/DKS-MANAGER)
