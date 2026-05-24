# C-MAPSS RUL Prediction

End-to-end pipeline for predicting Remaining Useful Life (RUL) of turbofan engines using NASA's C-MAPSS dataset.

## Status
🚧 In development — Day 1: project setup + data exploration.

## Dataset
[NASA C-MAPSS](https://www.nasa.gov/intelligent-systems-division) — turbofan engine degradation simulation. Four sub-datasets (FD001–FD004) with multivariate sensor readings under different operating conditions and fault modes.

## Setup
```bash
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

## Structure
- `notebooks/` — exploration
- `src/` — reusable modules
- `data/raw/` — original dataset (gitignored)
- `data/processed/` — derived datasets (gitignored)
- `models/` — trained models (gitignored)