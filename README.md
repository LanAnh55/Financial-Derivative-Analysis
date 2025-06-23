# Option Pricing Analysis for Hoa Phat Group (HPG)

## Overview

This repository contains a comprehensive financial data analysis project on the stock performance and option pricing of Hoa Phat Group (HPG), one of Vietnam's largest steel and industrial conglomerates. The study incorporates historical stock price modeling, future forecasting using stochastic processes, and derivative pricing via binomial tree models.

## Repository Structure
- `HPG-Yahoo Finance using R.Rmd`: install database
- - `HPG_VN.csv`: Historical daily stock price data for HPG (2007–2025) from Yahoo Finance.
- `Option_Pricing_Analysis_for_Hoa_Phat_Group_(HPG).ipynb`: Jupyter Notebook with Python code for data manipulation, visualization, and analysis.
- `Option Pricing Analysis for Hoa Phat Group (HPG).pdf`: Final analytical report summarizing theoretical models, analysis results, and investment recommendations.

## Project Highlights

- Fitting a normal distribution to daily returns of HPG stock from 2007 to 2025.
- Estimating drift (18.9%) and volatility (34.6%) using historical price data.
- Forecasting future prices using the Geometric Brownian Motion (GBM) model.
- Pricing 2-month European call and put options using the Binomial Option Pricing Model (BOPM).
- Quantitative and qualitative investment analysis, including ROI comparison with bank savings.

## Key Techniques

- **Statistical Modeling**: Gaussian fitting of daily returns.
- **Stochastic Simulation**: GBM for simulating future stock prices.
- **Options Pricing**: Binomial model implementation for call and put options.
- **Risk Assessment**: Profit-loss projections and hedging strategies.

## Results Summary

| Metric                                | Value                         |
|---------------------------------------|-------------------------------|
| Annual Drift                          | 18.9%                         |
| Annual Volatility                     | 34.6%                         |
| 3-Month Forecast Price (GBM)          | ₫34,336 ± ₫12,289             |
| 6-Month Forecast Price (GBM)          | ₫33,452 ± ₫11,754             |
| 12-Month Forecast Price (GBM)         | ₫32,555 ± ₫11,809             |
| European Call Option Price (2 months) | ₫740.80                       |
| European Put Option Price (2 months)  | ₫561.69                       |
| ROI since IPO (2007–2025)             | +932%                         |

## Data Sources

- Historical prices from [Yahoo Finance](https://finance.yahoo.com)
- Interest rate for risk-free return: 3-month HNX rate at 2.19%

## Tools and Libraries

- Python 3.x
  - `pandas`, `numpy`, `scipy`, `matplotlib`
- R (optional)
  - `quantmod`, `tidyverse`
- Jupyter Notebook
- RStudio (for `.Rmd`)

## How to Use

1. Clone this repository.
2. Ensure Python 3.x is installed.
3. Install required packages:

   ```bash
   pip install pandas numpy scipy matplotlib
4. Open the R Markdown file to install database
5. Open and run the Jupyter Notebook: Option_Pricing_Analysis_for_Hoa_Phat_Group_(HPG).ipynb
   
---

**Version:** 1.1.0

**Contact:** Nguyễn Thị Lan Anh ([lananh2004@gmail.com](lananh2004@gmail.com)) 
Data Analyst | Financial Modelling | Python & R Practitioner
