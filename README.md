# ECON_148_proj_3

Brief instructions to reproduce the analysis in `ECON_148_proj_3.ipynb`.

## What this repo contains
- `ECON_148_proj_3.ipynb` — main Jupyter notebook that runs data collection, cleaning, and model experiments (ordered logit, random forest, XGBoost).
- `country_codes.csv`, `sovereign_default_database.csv` — data files the notebook reads locally.
- `requirements.txt` — minimal Python package list for reproducing the environment.

## Prerequisites
- macOS (tested), any UNIX-like OS will work similarly.
- Python 3.9+ (3.10 or 3.11 recommended).
- Internet access is required for parts of the notebook that fetch data from the World Bank / IMF / Wikipedia.

## Quick reproduction steps
1. Create and activate a virtual environment (zsh):

```bash
python -m venv .venv
source .venv/bin/activate
```

2. Install required packages:

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

3. Start Jupyter (or use VS Code's Notebook UI) and open the notebook:

```bash
jupyter notebook ECON_148_proj_3.ipynb
```

4. Run the notebook cells top-to-bottom. Some cells download data from external services and may take a little time.