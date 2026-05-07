# Financial Econometrics - Project 1
## Best-Practices Handbook: Challenges in Time Series Modeling

---

## Overview
This project develops a best-practices handbook for quantitative 
analysts working with financial time series data. Using Apple Inc. 
(AAPL) daily return data from January 2018 to December 2025, the 
handbook identifies, demonstrates, and resolves five key challenges 
that affect the reliability of financial models.

---

## Dataset
| Attribute | Detail |
|---|---|
| **Asset** | Apple Inc. (AAPL) |
| **Source** | Yahoo Finance via yfinance API |
| **Period** | January 2018 - December 2025 |
| **Frequency** | Daily closing prices |
| **Units** | US Dollars (USD) |

---

## Challenges Covered

### Problem 1 - Skewness
Technical definition, demonstration using AAPL return 
distribution, Jarque-Bera normality test, histogram and 
Q-Q plot diagnostics, and directions for addressing 
asymmetric return distributions in financial modeling.

### Problem 2 - Sensitivity to Outliers
Identification of extreme return observations using 
Z-score and IQR methods, quantification of how the 
COVID-19 crash of March 2020 distorts volatility 
estimates, and robust modeling approaches to reduce 
outlier influence.

### Problem 3 - Overfitting
Train/test split analysis using polynomial regression 
of increasing complexity, bias-variance tradeoff 
visualisation, and cross-validation approaches for 
preventing overfitting in financial forecasting models.

### Problem 4 - Multicollinearity
Correlation matrix and Variance Inflation Factor (VIF) 
analysis using AAPL, MSFT, SPY, and GOOGL returns, 
demonstration of coefficient instability, and Ridge 
and Lasso regression as corrective approaches.

### Problem 5 (Step 4) - Lack of Interpretation
Demonstration of how raw statistical outputs become 
actionable financial insights through unit conversion, 
significance filtering, and plain-language translation 
of model coefficients.

---

## Repository Structure
financial-econometrics-project1/
│

├── Financial_Econometrics_Project1.ipynb   # Main notebook

└── README.md                               # This file

---

## How to Run
1. Open `Financial_Econometrics_Project1.ipynb` in 
   Google Colab or Jupyter Notebook
2. Run **Runtime → Run All**
3. All data is downloaded automatically via the 
   yfinance API - no manual data download required

---

## References
- Hull, John C. *Options, Futures, and Other Derivatives*. 
  10th ed., Pearson, 2018.
- Tsay, Ruey S. *Analysis of Financial Time Series*. 
  3rd ed., Wiley, 2010.

---

## Course Information
**Course:** Financial Econometrics / Applied Time Series  
**Project:** Project 1 - Best-Practices Handbook  
**Submitted to:** chitzlee@gmail.com
