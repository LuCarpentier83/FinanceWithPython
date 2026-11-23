# Finance with Python

Stock market analysis in Python. Technical indicators, risk metrics and statistics are
computed from scratch to understand the math behind trading strategies, instead of
relying on ready-made libraries.

## Contents

`notebooks/stock_analysis.ipynb`:

- Downloads historical prices from **Yahoo Finance** (`yfinance`) for a configurable ticker
  and period (S&P 500 by default)
- Explains the OHLCV columns and the difference between Close and Adjusted Close
- Computes daily returns and the metrics derived from them (cumulative return, volatility,
  histogram of returns)
- Plots prices, returns and indicators with Matplotlib and Seaborn

## Getting started

```bash
pip install -r requirements.txt
jupyter lab notebooks/stock_analysis.ipynb
```

## License

Apache 2.0. See [LICENSE](LICENSE).
