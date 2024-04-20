# Cointegration-of-Bond-Yields
 Testing Cointegration of Bond Yields using various statistical methods

### Summary of the Notebook: "Cointegration Bond Yields"

This Jupyter notebook delves into the statistical analysis of bond yields to examine cointegration among different financial securities. The notebook uses Python libraries such as `pandas` for data handling, `statsmodels` for statistical tests and models, `matplotlib` and `seaborn` for plotting, and `eikon` for fetching financial data.

### Detailed Explanation

The notebook's primary focus is on performing time-series analysis to understand the relationships between various bond yields. It includes detailed steps to fetch, preprocess, and analyze the data.

**Key steps in the notebook include:**
- **Data Acquisition and Cleaning**: Data is loaded from Excel files and databases using `pandas` and `openpyxl`, followed by cleaning steps such as dropping missing values and filling gaps with backfill methods.
- **Differencing Data**: To prepare for cointegration testing, the data is differenced to make it stationary, a requirement for such analysis.
- **Statistical Testing for Stationarity and Cointegration**:
  - Augmented Dickey-Fuller (ADF) tests are conducted to check the stationarity of the time series data.
  - Engle-Granger two-step method is hinted to test for cointegration among the bond yields.
- **Modeling and Analysis**: Various statistical models, including OLS regression, are employed to model the relationships between the bond yields and understand the dynamics of these financial instruments.

The notebook is structured to provide a comprehensive workflow from data ingestion to detailed statistical analysis, using advanced techniques like cointegration to study financial time series data. This approach helps in identifying long-term equilibrium relationships between different bonds, aiding in investment decision-making and risk management.