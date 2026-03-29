# Loan Repayment Prediction — PJATK Data Science Club

Binary classification competition predicting loan repayment probability, evaluated on AUC-ROC.

## Notebooks
- `01_eda.ipynb` — Exploratory Data Analysis
- `02_model.ipynb` — LightGBM + CatBoost ensemble with Optuna tuning

## Results
- Public leaderboard AUC: 0.92759
- Best strategy: 50/50 blend of hypertuned LightGBM and CatBoost
- Backup strategy: single hypertuned LightGBM


## Data
Download the datasets from the [Kaggle competition](https://www.kaggle.com/competitions/forecasting-loan-repayment) and place them in the `data/` folder:
- `train.csv`
- `test.csv`
- `original.csv`

## Setup
```bash
pip install -r requirements.txt
```

## Notes
- Detailed methodology, results, and reproducibility notes are documented within each notebook and particularly in the summaries at the end
- Full pipeline requires GPU for practical runtime — see reproducibility notes in `02_model.ipynb` for details.
