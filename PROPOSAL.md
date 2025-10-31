# Project Title and Category :
# Title :
Estimating the Federal Reserve’s Policy Reaction Function
# Category :
Statistical Analysis Tools
# Problem statement :
Central banks adjust their interest rates based on inflation and the economic situation. I will use the Taylor rule to formalize this relationship, although the exact parameters may vary from one central bank to another or over time. My goal is to empirically estimate the FED's reaction function in to understand how it adjusts its monetary policy decisions.
# Motivation :
Combine my knowledge of economics (macro/monetary) with my skills in data science (analysis, modeling, interpretation) to understand how the FED sets its key interest rate based on inflation and the output gap, and draw conclusions based on actual data
# Planned approach and technologies :
For the data, my likely sources will probably be FRED or CSV (public databases).

For my methodology, I will clean and align the data, ensure consistent frequency, and test for stationarity. I will estimate the classic Taylor rule and compare it with a more expanded version that includes the lagged rate. I will use OLS regressions and also perform robustness analyses (significance tests, residual diagnostics, R^2).

For visualization purposes, I will plot the adjusted key rates against the actual rates and illustrate the differences.

For technology, I will use tools such as pandas, numpy, statsmodels, and matplotlib.
# Expected challenges and how to overcome them :
The likely difficulties are data quality and frequency, measurement of the output gap, stationarity of time series, and econometric interpretation (autocorrelation, multicollinearity).

Solutions to overcome these difficulties include data cleaning, stationarity testing, simple regularization, and specification comparison.
# Success criteria :
The model accurately reproduces past Fed decisions, i.e., a high R^2 and a low forecast error. The estimated rule has coefficients that are economically consistent, responding positively to inflation and moderately to the output gap. Technical success will also be measured through well-documented, reproducible code and consistent regression diagnostics.
# Stretch goals (if time permits) :
If time permits, I could extend the analysis to include another bank such as the SNB for comparison purposes, as well as compare several periods (before/after 2008), test non-linear rules and/or incorporate shocks (crises, COVID, etc.).


