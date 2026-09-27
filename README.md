# Market Regime Modeling

A Python-based collection of quantitative research notebooks for identifying, analysing, and trading financial market regimes using statistical and state-space models.

The project focuses on **Hidden Markov Models (HMMs)**, **multivariate regime detection**, **regime persistence**, **volatility regimes**, **regime-switching trading strategies**, and **Kalman filtering**.

## Project Overview

Financial markets often transition between distinct states such as:

- Bull and bear regimes
- High- and low-volatility environments
- Trending and mean-reverting periods
- Risk-on and risk-off conditions

This repository explores statistical methods for detecting these latent market states and studying how they can be incorporated into quantitative investment and trading frameworks.

## Notebooks

| Notebook | Description |
| --- | --- |
| `Market regime detection.ipynb` | Detects different market regimes using statistical and machine-learning techniques. |
| `Multivariate HMM.ipynb` | Extends regime detection to multiple financial variables using a multivariate Hidden Markov Model. |
| `Hmm regime prediction.ipynb` | Explores the use of HMMs for estimating and predicting latent market regimes. |
| `Regime persistence analysis.ipynb` | Analyses how long detected regimes persist and studies regime transition behaviour. |
| `Regime switching trading.ipynb` | Investigates trading strategies that adapt portfolio positioning according to the detected market regime. |
| `Volitility regime.ipynb` | Examines changes between different market-volatility environments. |
| `HMM + kalman filter.ipynb` | Combines Hidden Markov Models with Kalman filtering for dynamic state estimation and regime analysis. |

## Key Methods

- Hidden Markov Models
- Multivariate HMMs
- Markov regime switching
- Kalman filtering
- State-space modelling
- Volatility regime analysis
- Transition probability estimation
- Regime persistence analysis
- Quantitative trading strategy design
- Financial time-series analysis

## Technology

- Python
- Jupyter / Google Colab
- NumPy
- pandas
- Matplotlib
- scikit-learn
- statsmodels
- HMM / state-space modelling libraries

Specific package requirements may vary by notebook.

## How to Use

Clone the repository:

```bash
git clone https://github.com/gourujeevan-cpu/market-regime-modeling.git
cd market-regime-modeling
```

Then open any notebook in Jupyter Notebook, JupyterLab, VS Code, or Google Colab.

## Applications

The techniques explored in this project can be applied to:

- Asset allocation
- Tactical portfolio positioning
- Risk management
- Volatility forecasting
- Systematic trading
- Macro regime analysis
- Market timing research
- Dynamic hedging

## Author

**Gouru Jeevan Reddy**

- MSc Finance & Economics, London School of Economics
- IIT (BHU) Varanasi
- GitHub: https://github.com/gourujeevan-cpu
- LinkedIn: https://www.linkedin.com/in/gouru-jeevan-reddy-671b90157/

## Disclaimer

This repository is intended for educational and research purposes only. It does not constitute investment advice or a recommendation to trade any financial instrument.
