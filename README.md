# Neural ODE Paradigms for Seasonal Influenza Forecasting

This repository contains the code and data for the final project of **EN.560.652.01.FA25: Scientific Machine Learning**.

## 📄 Project Overview
We investigate the efficacy of Neural Ordinary Differential Equations (Neural ODEs) in modeling Maryland's influenza-like illness (ILI) data (2018-2024). We systematically compare four modeling paradigms:
- **M0**: Classical SEIRS Baseline
- **M1**: White-box Neural ODE (Physics-based)
- **M2**: Black-box Neural ODE (Pure Data-driven)
- **M3**: Grey-box Neural ODE (Universal Differential Equations / Residual Learning)
- **M4**: LSTM Baseline

## 📂 Repository Structure
- `data/`: Pre-processed ILINet data for Maryland.
- `models/`: PyTorch implementations of White, Black, and Grey-box models using Neuromancer.
- `figures/`: Generated plots used in the report.
- `main.py`: Main script to reproduce all experiments and figures.

## 🚀 Quick Start
1. Install dependencies:
   ```bash
   pip install torch neuromancer matplotlib pandas
