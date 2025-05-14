# CO₂ Flux Analysis – Supplementary Material

This repository contains supplementary code and data for the master's thesis on CO₂ fluxes in glacier-fed river systems. The primary focus is on R-based Jupyter Notebooks used for data analysis and visualization.

## 🔍 Notebooks

The main analysis is conducted in:

- `/notebooks/CO2_Flux_Final.ipynb`

You can run the notebooks directly in your browser using Binder:

[![Launch Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/kokkaso/MA_supplementary_Data/HEAD?filepath=notebooks%2FCO2_Flux_Final.ipynb)

> No installation required – Binder automatically sets up the R environment and dependencies.

## 📁 Repository Structure

```
.
├── data/            # Raw data files (.ods)
├── notebooks/       # R Jupyter Notebooks (main analysis here)
├── config/          # Binder environment configuration
├── scripts/         # Additional helper R scripts (if needed)
└── README.md        # Project description
```

## ⚙️ Environment

Binder uses:

- `config/runtime.txt` – specifies R version
- `config/install.R` – installs required R packages (e.g. ggplot2, readODS, officer)

These files ensure a reproducible analysis environment.

## 📜 License

For academic use only. Please contact the author for questions or reuse.
