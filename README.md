# Pairs Trading with Machine Learning ✨

**Author**: Nabyl H.  
**Course**: Certificate in Python for Finance (CPF)  
**Date**: April 2026

## Overview

This project implements a pairs trading strategy on the ETF pair EWA (Australia) and EWC (Canada) from 2015 to 2024.  
A traditional z-score baseline is compared with a Random Forest classifier that predicts mean reversion opportunities.

## Key Results (Test Period – last 20% of data)

| Metric            | Baseline (Z-Score) | Random Forest |
|-------------------|--------------------|---------------|
| Total return (net)| 68.30%             | 15.89%        |
| Sharpe ratio      | 5.06               | 0.82          |
| Max drawdown      | -5.80%             | -8.54%        |
| Win rate          | 16.73%             | 49.39%        |
| Number of trades  | 9                  | 8             |

## Run on Google Colab

Click the badge to open the notebook directly:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Quantx73/pairs-trading-ml-v2/blob/main/notebooks/Pairs_Trading_ML_final.ipynb)

## Repository Structure

pairs-trading-ml-v2/
├── data/
│ └── etf_pairs.csv # EWA/EWC daily prices (2015-2024)
├── notebooks/
│ └── Pairs_Trading_ML_final.ipynb # Main notebook
├── src/ # (optional) Python modules
├── requirements.txt # Dependencies
└── README.md


## Disclaimer on AI Usage

This project was developed with occasional assistance from a large language model (code suggestions, debugging). All final code was written, tested, and validated by the author. The overall structure and financial analysis are original.

## License

Educational use only – CPF certification.