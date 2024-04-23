# Comparative-Analysis-of-SARIMA-and-LSTM-for-Financial-Forecasting
Explore the dynamics of City Bank and Wells Fargo stock prices through comprehensive time series analysis, uncovering seasonal patterns and employing advanced forecasting techniques such as SARIMA and LSTM models to predict future price movements with accuracy.


**Financial Time Series Analysis and Forecasting**

**Overview:**
This project focuses on analyzing the historical stock prices of City Bank (CB) and Wells Fargo (WF) using time series analysis techniques. It explores seasonal patterns, tests for stationarity, and applies advanced forecasting models including SARIMA and LSTM to predict future stock price movements.

**Key Features:**

**Data Collection**: Historical stock price data for City Bank and Wells Fargo are collected from Yahoo Finance using the yfinance library.
**Exploratory Data Analysis (EDA)**: The project begins with visualizing the closing prices of both stocks and decomposing their seasonal components to understand underlying patterns.
**Stationarity Testing**: Augmented Dickey-Fuller tests are conducted to assess the stationarity of the time series data.

**Modeling**:

**SARIMA**: Seasonal AutoRegressive Integrated Moving Average models are fitted to capture the seasonal patterns in the data and make forecasts.
**LSTM**: Long Short-Term Memory networks are implemented to capture complex temporal dependencies and improve forecasting accuracy.

**Evaluation**: Model performance is evaluated using root mean squared error (RMSE) to measure the accuracy of the forecasts.
**Visualization**: Results are visualized using matplotlib and plotly to illustrate actual vs. predicted stock prices and forecasted trends.

**Project Structure:**

**financial_analysis.ipynb**: Jupyter Notebook containing the code for data collection, analysis, modeling, and visualization.
**README.md**: This file, providing an overview of the project, its features, and structure.


**Requirements**:

Python 3
**Libraries**: pandas, numpy, yfinance, matplotlib, statsmodels, scikit-learn, tensorflow, plotly

**Usage:**

Clone the repository: git clone https://github.com/yourusername/financial-time-series-analysis.git
Install the required libraries: pip install -r requirements.txt
Run the Jupyter Notebook financial_analysis.ipynb to execute the code and generate insights.
