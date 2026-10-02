# Car Price Regression

Explore car attributes, normalize company names, engineer fuel-economy and price-range features, encode categories, and compare regression models.

**Stack:** Python · pandas · scikit-learn · Jupyter

## Run locally

```bash
git clone https://github.com/abiy8/OIBSIP_Task3.git
cd OIBSIP_Task3
python -m venv .venv
# Activate .venv for your operating system.
pip install jupyter pandas numpy scikit-learn matplotlib seaborn statsmodels
jupyter notebook
```

Open `OIBSIP_Task3.ipynb` and run cells in order from the repository directory. Input data is included in `CarPrice.csv`.

## Context and limitations

Oasis Infobyte task / learning project. The notebook derives price-range features from target prices before splitting and scales full-data features. This can leak target or test information. Several final calls reverse the arguments to `r2_score`. Existing scores should not be treated as validated performance.
