# S&P 500 Stock Data Forecasting with AutoTS

This project provides a Python-based implementation for fetching historical stock data of S&P 500 companies, performing time series forecasting using the `AutoTS` library, and visualizing the original vs. forecasted data. The workflow includes fetching data from Yahoo Finance, preprocessing it, running machine learning-based time series forecasting models, and generating performance metrics.

---

## Features

- **Data Collection**: Fetch historical stock data for selected S&P 500 companies using the `yfinance` library.
- **Customizable Forecasting Models**: Implements the `AutoTS` library for time series forecasting with a list of selected models.
- **Weighted Metrics**: Configurable weights for time series columns (`Open`, `Close`, `High`, `Low`).
- **Visualization**: Plots original and forecasted values using `Plotly` for interactive data visualization.
- **Model Insights**: Extracts unique models used in ensemble forecasts and performance metrics.

---

## Prerequisites

1. **Python 3.8+**: Ensure Python is installed on your system.
2. **Dependencies**:
    - `yfinance`
    - `pandas`
    - `autots`
    - `plotly`

Install dependencies using:
```bash
pip install yfinance pandas autots plotly
