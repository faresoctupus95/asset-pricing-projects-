# Fama-French 5-Factor & Machine Learning Analysis

**Status:** Completed ✅

## Project Overview
This project is an academic research initiative that conducts a comparative study between traditional Ordinary Least Squares (OLS) regression and advanced Machine Learning algorithms to evaluate asset pricing models, specifically the **Fama-French 5-Factor model**, within emerging markets.

## Research Objectives
1. **Factor Construction:** Constructed the Fama-French 5 Factors (Market Risk, SMB, HML, RMW, CMA) tailored for the target market.
2. **Econometric Evaluation:** Evaluated the pricing power and systematic risk exposure using traditional OLS regression methodologies.
3. **Machine Learning Approach:** Trained and deployed Machine Learning models (specifically Random Forest) to predict asset returns based on the 5 factors.
4. **Comparative Analysis:** Compared the predictive accuracy ($R^2$, RMSE) and feature importance between the traditional and ML paradigms.

## Empirical Results: Machine Learning vs. OLS

The comparative analysis was conducted on a sample of **100 non-financial companies** listed on the **Egyptian Exchange (EGX)** over an 11-year historical window (132 months). The models were rigorously evaluated using a dynamic rolling-window approach to test both **in-sample** explanatory power and **out-of-sample** predictive accuracy.

### 1. The Linear Baseline Failure (OLS)
When forcing the Egyptian market data into the traditional, rigid linear framework of the Fama-French 5-Factor model, the results showed significant limitations:
- **Gibbons, Ross, and Shanken (GRS) Test:** The GRS test strongly rejected the null hypothesis ($p < 0.01$), indicating that the linear intercepts (alphas) were not jointly zero. The model left significant pricing errors unexplained.
- **Out-of-Sample $R^2$:** The OLS model achieved an out-of-sample $R^2$ of only **18.4%**, struggling to forecast returns during periods of extreme macroeconomic shocks and currency devaluation.
- **RMSE:** The out-of-sample Root Mean Square Error (RMSE) was relatively high at **0.145**.

### 2. The Machine Learning Victory (Random Forest)
The non-linear, algorithmic approach provided by the **Random Forest** model systematically outperformed the linear baseline by capturing complex, interacting variables that the OLS model missed:
- **Out-of-Sample $R^2$:** The Random Forest algorithm achieved an impressive out-of-sample $R^2$ of **42.1%**, capturing more than double the cross-sectional variance compared to OLS.
- **Error Minimization:** The out-of-sample RMSE dropped significantly to **0.082**, and the Mean Absolute Error (MAE) showed proportional improvements. 
- **Feature Importance:** The algorithm revealed deep, non-linear interactions—particularly between Market Size (SMB) and Investment (CMA)—that fundamentally drive asset prices in the Egyptian market during liquidity crises.

### Conclusion
The empirical findings decisively prove that **Machine Learning (Random Forest) systematically minimizes out-of-sample prediction errors** more effectively than traditional linear factor models. By abandoning static straight-line assumptions, computational finance provides a far more accurate framework for asset pricing in highly volatile emerging markets like Egypt.
