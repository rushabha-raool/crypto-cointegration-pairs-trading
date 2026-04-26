# Crypto Futures Cointegration Analysis

Statistical pairs trading study on SOL/USD and BTC/USD using cointegration analysis, residual diagnostics, Z-score signal generation, and bootstrap permutation testing for Sharpe ratio significance.

## Project Status
🚧 In progress

## Methodology
1. Stationarity testing (ADF, KPSS) on log prices and returns
2. Engle-Granger cointegration test with OLS spread regression
3. Residual diagnostics (Ljung-Box, Jarque-Bera, Breusch-Pagan, ARCH-LM)
4. Z-score signal generation and threshold-based trading rules
5. Backtesting with Sharpe ratio computation
6. Bootstrap permutation testing for statistical significance

## Tech Stack
Python · pandas · NumPy · statsmodels · SciPy · arch · yfinance · matplotlib

## Setup
```bash
git clone https://github.com/rushabha-raool/crypto-cointegration-pairs-trading.git
cd crypto-cointegration-pairs-trading
python -m venv .venv
source .venv/bin/activate  # Mac/Linux
pip install -r requirements.txt
```

## Notebooks
- `01_data_acquisition.ipynb` — Data pull and exploratory analysis
- `02_stationarity_tests.ipynb` — ADF and KPSS testing
- `03_cointegration.ipynb` — Engle-Granger cointegration
- `04_residual_diagnostics.ipynb` — Regression diagnostics
- `05_signal_generation.ipynb` — Z-score-based trading signals
- `06_backtest.ipynb` — Strategy backtest and Sharpe
- `07_bootstrap_significance.ipynb` — Permutation testing

## Author
Rushabha Raool · [LinkedIn.com/in/rushabha-raool]