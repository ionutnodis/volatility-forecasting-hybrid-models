# Volatility Forecasting with Hybrid Models

This project compares traditional econometric volatility models (ARCH/GARCH) with machine learning models (Random Forest, LSTM) for daily volatility forecasting on S&P 500 stocks.

## Goals
- Forecast one-day-ahead realized volatility
- Compare:
  - Forecast accuracy (RMSE, MAE, MAPE)
  - Training and prediction time
  - Explainability using SHAP (RF) and ALE (LSTM)

## Repo Structure
- `data/` — Raw and processed datasets
- `notebooks/` — Jupyter notebooks
- `src/` — Core code modules
- `results/` — Visualizations, metrics, and SHAP/ALE outputs

## License
MIT
