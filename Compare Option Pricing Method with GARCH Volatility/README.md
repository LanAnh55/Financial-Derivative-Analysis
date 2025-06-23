# Financial-Derivative-Analysis: Option Pricing Analysis for Hoa Phat Group (HPG)

This repository contains a professional analysis of **European-style options** on *Hoa Phat Group (HPG)* stock using Python. The project applies financial econometrics and derivatives pricing techniques to evaluate call and put options under different volatility models.

---

## Project Overview

- **Objective**: Price European call/put options for HPG using:
  - Black-Scholes model
  - Binomial Tree (CRR)
  - Monte Carlo simulation
- **Data**: Daily stock prices of HPG (12/14/2007–6/20/2025)
- **Volatility Models**:
  - Historical volatility (35.18%)
  - GARCH(1,1) forecast volatility (24.48%)

---

## Key Findings

- HPG returns are **non-normally distributed** and exhibit **autocorrelation**, confirmed via statistical tests.
- **GARCH volatility** yields significantly lower option prices vs. historical volatility (≈30% lower).
- All three pricing models produce **consistent results** across both volatility inputs.

| Volatility Source | Model          | Call (VND) | Put (VND) |
|-------------------|----------------|------------|-----------|
| Historical        | Black-Scholes  | 1,109.22   | 1,060.75  |
| GARCH             | Black-Scholes  | 779.50     | 731.04    |

---

## Tech Stack

- **Language**: Python 3
- **Libraries**: `pandas`, `numpy`, `matplotlib`, `scipy`, `statsmodels`, `arch`, `yfinance`

Install with:
```bash
pip install pandas numpy matplotlib scipy statsmodels arch yfinance
```

---

## Files
- `HPG-Yahoo Finance using R`: download data file 
- `HPG_VN.csv`: Cleaned historical price data
- `Option_Pricing_Analysis_for_Hoa_Phat_Group_(HPG).ipynb`: Source code + visualizations
- `*.pdf`: Final report with analysis and interpretation

---

Financial Derivatives Project – June 2025  
*Advanced option pricing & time-series modeling for equity derivatives.*
---

**Version:** 1.1.0

**Contact:** Nguyễn Thị Lan Anh ([lananh2004@gmail.com](lananh2004@gmail.com))

