# Factor Investing and Asset Pricing Analysis

## Overview

This project applies empirical asset pricing models to study how stock returns are related to systematic risk factors.

Rather than focusing on short-term price prediction, this project examines whether common risk factors can explain differences in stock returns across companies.

The analysis uses the Fama-French Three Factor Model to estimate factor exposures and evaluate the role of market, size, and value factors.

---

## Research Question

Can Fama-French factor exposures explain differences in stock returns among individual companies, and how well is the explanation.

---

## Methodology

The project includes:

- CAPM regression to estimate market exposure
- Fama-French Three Factor Model regression
- Time-series regression to estimate factor loadings and alpha
- Cross-sectional regression to analyse the relationship between factor exposures and returns
- Portfolio performance evaluation using risk-adjusted metrics

---

## Data

The analysis uses historical return data for five individual stocks:

- Apple (AA)
- Microsoft (MSFT)
- Tesla (TSLA)
- Berkshire Hathaway (BRK.B)
- JPMorgan Chase (JPM)

Factor data is obtained from the Fama-French Three Factor Research Dataset, including:

- Market factor (MKT-RF)
- Size factor (SMB)
- Value factor (HML)

---

## Tools

The project is implemented in Python using:

- Pandas for data processing
- NumPy for numerical analysis
- Statsmodels for regression modelling
- Matplotlib for data visualisation

---

## Results

The project estimates:

- Market beta
- SMB and HML factor exposures
- Jensen's alpha

The estimated factor loadings are used to analyse how different companies are exposed to systematic risk factors and to evaluate portfolio performance using metrics such as the Sharpe ratio.

---

## Files
