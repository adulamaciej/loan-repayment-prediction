# Loan Repayment Prediction — PJATK Data Science Club

Binary classification competition predicting loan repayment probability, evaluated on AUC-ROC.

## Notebooks
- `01_eda.ipynb` — Exploratory Data Analysis
- `02_model.ipynb` — LightGBM + CatBoost ensemble with Optuna tuning

## Results
- Public leaderboard AUC: 0.92759
- Best strategy: 50/50 blend of hypertuned LightGBM and CatBoost
- Backup strategy: single hypertuned LightGBM


## Notes
Detailed methodology, results, and reproducibility notes are documented within each notebook.