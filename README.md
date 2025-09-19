
Project Aim / Objectives:

An automated live data fetcher, which uses return data of the S&P 500, interest rate data, inflation indidcators 
amongst other macroeconomic factors to determine influence of each using simple regression analysis. 
Combines live financial data retrieval, regression modell=ing and strategy backtesting in a single, reproducible notebook. 

Key Features:
- Computes monthly returns and lagged variables, caputuring delayed market reaction.
- Rolling 12-month regression, tracking how factor sensitivities evolve over time, highlighting periods of differing influence.
- Visuals, generates clear, professional plots of factor coefficients and cumulative returns.
- OLS regression, macroeconomic factors including standardised coefficients for eased comparison.

Tech Stacks: Python pandas, numpy, yfinance, statsmodel, matplotlib, scikit-learn
