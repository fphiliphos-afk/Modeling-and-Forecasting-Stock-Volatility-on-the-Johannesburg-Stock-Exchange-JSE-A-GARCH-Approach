# Modeling-and-Forecasting-Stock-Volatility-on-the-Johannesburg-Stock-Exchange-JSE-A-GARCH-Approach
This project applies Generalized Autoregressive Conditional Heteroskedasticity (GARCH) models to analyze and forecast stock market volatility on the Johannesburg Stock Exchange (JSE).
The study uses Standard Bank (SBK.JO) data (downloaded via Yahoo Finance) to:

**Perform exploratory data analysis (EDA) of stock prices and returns**

**Estimate volatility using GARCH(1,1) and GARCH(2,2) models**

**Compare model fit using AIC/BIC and parameter significance**

**Forecast volatility for 5–10 business days ahead**

**Visualize conditional volatility and forecasts**

# **⚙️ Tools & Libraries**

Python (Jupyter Notebook)

pandas, numpy → data processing

matplotlib → visualization

statsmodels → statistical tests (ADF)

arch → GARCH modeling

# **Key Results**

GARCH(1,1) was selected as the optimal model due to:

Lower AIC/BIC values than GARCH(2,2)

Parsimonious structure (fewer but significant parameters)

Better out-of-sample forecast accuracy

Volatility persistence was high (α + β ≈ 0.97), a common feature of financial time series.

Forecasts indicate short-term increases in volatility, relevant for risk management and investment decisions.
