# Crypto Market Analysis (CoinGecko) — 24H Price Change Forecasting

This project pulls real-time cryptocurrency market data from the CoinGecko API, cleans and explores the dataset, engineers features, and trains a regression model to forecast **24-hour price change**. The goal is to combine market analytics + modeling to understand which signals relate most to short-horizon movement.

## Tech Stack
- Python: pandas, NumPy
- Modeling: scikit-learn
- Visualization: Matplotlib, Seaborn
- Data Source: CoinGecko API

## Key Results
- Built a regression pipeline to predict **24-hour price change**
- Achieved **R² ≈ 0.78** on evaluation
- Engineered market features such as volatility-style metrics, liquidity ratio, market-cap grouping, and volume-to-market-cap ratio
- Analyzed 100+ crypto assets pulled at runtime from CoinGecko

## Dataset
- Source: CoinGecko API (market endpoints)
- Data is pulled live, so results may vary slightly depending on when the script is run

## How to Run
### Option A: Jupyter Notebook (recommended)
1. Clone the repo
2. Install dependencies
```bash
pip install -r requirements.txt

