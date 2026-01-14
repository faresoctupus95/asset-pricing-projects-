# Project 01 — CAPM & Beta Estimation  
**Asset Pricing Projects Series**

This project empirically applies the **Capital Asset Pricing Model (CAPM)** to estimate the **systematic risk (Beta)** of a stock and compute its **expected return**.

The objective is to answer a fundamental asset pricing question:

> **How risky is this stock relative to the market, and how should that risk be priced?**

---

## 📊 CAPM Beta Regression (AAPL vs Market)

The chart below shows the **daily return regression of Apple Inc. (AAPL) against the S&P 500**, where the slope of the regression line represents **Beta**.

![CAPM Beta Regression](capm_beta_regression.png)

---

## 🔬 Methodology

- **Asset:** Apple Inc. (AAPL)
- **Market Proxy:** S&P 500 Index (^GSPC)
- **Time Period:** 2019 – 2024
- **Frequency:** Daily returns
- **Model:**  
  \[
  R_{stock} = \alpha + \beta R_{market} + \varepsilon
  \]

The regression is estimated using **Ordinary Least Squares (OLS)**.

---

## 📈 Key Results & Interpretation

- **Beta ≈ 1.21**  
  → Apple is **21% more volatile than the market**, confirming that large-cap tech stocks are **aggressive assets**.

- **R-Squared ≈ 0.64**  
  → About **64% of Apple’s price movement is explained by market movements**.

### The Asset Pricing Question
> **What explains the remaining 36% of returns?**

This motivates the transition to **multi-factor models**, such as **Fama-French**, in subsequent projects.

---

## 💰 CAPM Expected Return

The expected return is computed using:

\[
E[R] = R_f + \beta (E[R_m] - R_f)
\]

- **Risk-Free Rate:** 4%
- **Market Risk Premium:** 5.5%
- **Expected Annual Return (CAPM):** ~10.7%

---

## 🛠 Tools & Libraries

- Python
- `yfinance`
- `pandas`, `numpy`
- `statsmodels`
- `matplotlib`

---

## 📂 Files

- `capm_beta_analysis.py` — CAPM regression & pricing logic  
- `capm_beta_regression.png` — Beta regression visualization  

---

## 🔗 Next Project

➡ **Project 02: Fama–French Multi-Factor Model**  
Explaining the portion of returns **CAPM cannot capture**.

---

**Author:** Fares Awwad-Zeidan  
**Repository:** Asset Pricing Projects

