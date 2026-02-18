# crypto-market-analysis
#Cryptocurrency Market Analysis (CoinGecko) — 24H Price Change Forecasting

This project pulls real-time cryptocurrency market data from the CoinGecko API, cleans and explores the dataset, engineers features, and trains a regression model to forecast **24-hour price change**. The goal is to combine market analytics + modeling to understand which signals are most related to short-horizon movement.

## Tech Stack
- **Python**: pandas, NumPy
- **Modeling**: scikit-learn
- **Visualization**: Matplotlib / Seaborn (or Plotly if you used it)
- **Data Source**: CoinGecko API

## Key Results
- Built a regression pipeline to predict **24-hour price change**
- Achieved **R² ≈ 0.78** on evaluation (based on your current run/results)
- Engineered market features such as:
  - volatility-style metrics
  - liquidity ratio
  - market-cap grouping
  - volume-to-market-cap ratio

## Dataset
- Source: CoinGecko API (real-time market endpoints)
- Scope: 100+ crypto assets (pulled at runtime)
- Output: JSON → cleaned tabular dataset (CSV optional)

## Project Workflow
1. **Ingest** market data from CoinGecko (requests → JSON)
2. **Clean** and standardize fields (types, missing values, outliers)
3. **EDA** to understand distributions and relationships
4. **Feature engineering** to create higher-signal predictors
5. **Modeling** using scikit-learn regression
6. **Evaluation** using R² and error metrics

## How to Run
### Option A: Jupyter Notebook
1. Clone the repo
2. Install dependencies
```bash
pip install -r requirements.txt
