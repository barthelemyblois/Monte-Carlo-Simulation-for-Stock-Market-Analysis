# Monte Carlo Simulation of Stock Prices with Historical and GARCH-based Volatility

This project investigates the use of Monte Carlo methods to simulate future stock price paths using two approaches:

- A constant-volatility model based on Geometric Brownian Motion (GBM)
- A time-varying volatility model using GJR-GARCH(1,1) with Student's t-distributed errors

## Objectives

The notebook performs the following tasks:

- Downloads and processes historical stock data (AAPL)
- Calculates log returns and fits a GJR-GARCH(1,1) model
- Simulates future price trajectories using:
  - Constant volatility (historical estimate)
  - GJR-GARCH conditional volatility
- Plots simulated paths along with historical prices
- Computes 95% confidence intervals for forecasted prices
- Estimates Value-at-Risk (VaR) at 95% and 99% confidence levels

## Contents

The Jupyter notebook includes:

- Step-by-step explanations of the models and methodology
- Python code to estimate and simulate each model
- Graphical comparison of constant-volatility and GJR-GARCH simulations
- Evaluation of model realism through path behavior and risk measures
- Documentation of all functions and output interpretations

## How to Use

1. Clone or download this repository.
2. Open the notebook `monte_carlo_with_volatility_models.ipynb` using:
   - Jupyter Notebook
   - JupyterLab
   - Google Colab (if preferred)

## Requirements

To run the notebook, install the following Python packages:

```bash
pip install yfinance pandas numpy matplotlib seaborn statsmodels arch scipy

You can install these dependencies with the command :

bash
Copy the code
pip install yfinance pandas numpy matplotlib scipy
