## Hi everyone, I'm Nam

<!--
**HaiNam19/HaiNam19** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
I’m Nam, currently learning and growing toward becoming a Data Scientist. I have a strong foundation in statistics, machine learning, and data analysis. I enjoy working with data to answer meaningful questions, uncover patterns, and support better decisions.

My core expertise is centered around statistical analysis, with a particular focus on:
  - Hypothesis testing:  Designing experiments, formulating hypotheses, applying parametric tests, and using non-parametric methods (e.g., bootstrap) when assumptions fail.
  - Regression analysis: Building and diagnosing OLS/logistic models, handling multicollinearity and regularization, for both prediction and inference.  
  - Machine Learning: Solid understanding of regression and tree-based models, with a focus on tuning gradient boosting (XGBoost, LightGBM).
  - Causal inference: Moving beyond correlation via potential outcomes, randomized controlled trials, and A/B testing.

## Tech Stack

  ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
  ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
  ![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
  ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
  ![statsmodels](https://img.shields.io/badge/statsmodels-4B8BBE?style=flat)
  ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=matplotlib&logoColor=white)

  
  ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

  
  ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)


## Featured Projects

### 📈 [Cross-Sectional Factor Investing for Crypto Market](https://github.com/HaiNam19/Statistical-Factor-and-Machine-Learning-for-Crypto-Cross-Sectional-Alpha)
Built a long-short strategy by ranking coins on statistical factors instead of predicting absolute prices. The pipeline follows a professional quant workflow: point-in-time universe → raw factor construction → statistical validation (Spearman IC, Fama-MacBeth, tertile spread) → walk-forward composite alpha → backtest with realistic transaction costs. 

**Result:** OOS over 1,096 days — total return 448%, annualized return 61.7%, annualized volatility 42.4%, Sharpe 1.46, Sortino 2.16, max drawdown 38.2%, win rate 56.4%, Newey-West t-stat 2.54 (p = 0.011). Rolling Sharpe revealed the alpha is market-regime dependent rather than uniformly distributed over time — an honest limitation documented in the report.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![statsmodels](https://img.shields.io/badge/statsmodels-4B8BBE?style=flat)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=flat)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)

### 🏦 [Credit Risk Modeling: Probability of Default (PD) Scorecard](https://github.com/HaiNam19/Credit-Risk-Modeling)
Developed an end-to-end Probability of Default scorecard on the Home Credit dataset, following a real banking workflow: feature engineering across 6 raw tables → fine classing and WOE transformation → logistic regression scorecard → validation. 

**Result:** Final model with 37 variables after a 216 → 37 feature selection funnel. Gini ≈ 0.52 and KS ≈ 0.39 stable across train, validation, and test sets (gap < 0.01, no overfitting). Bad rates decrease monotonically across score deciles. Population shift sensitivity analysis showed the model stays robust under a higher-risk portfolio (Gini 0.526, AUC 0.763) and degrades only mildly under a concentrated medium-risk portfolio (Gini 0.43, AUC 0.71).

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=matplotlib&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![statsmodels](https://img.shields.io/badge/statsmodels-4B8BBE?style=flat)
