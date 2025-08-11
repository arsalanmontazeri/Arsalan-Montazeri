# My name is Arsalan, and I am Northeastern University graduated in Data analysis.
# I am advanced in SQL
# Gold Price Time Series & Machine Learning Prediction
(Tech Stack: Python, Pandas, NumPy, scikit-learn, XGBoost, Matplotlib, Seaborn
📂 Dataset: 660 days of OHLCV gold price data (2023–2025)
Project Overview
An end-to-end gold price prediction system combining time series analysis, technical indicators, and machine learning. Achieved 95.21% R² and 95.91% prediction accuracy using Ridge Regression. Designed a production-ready pipeline for real-time trading strategies.
Key Features
Data Cleaning: Converted European decimal formats, handled timestamps, validated OHLC consistency.
Time Series Analysis: Decomposition into trend, seasonal, residual; volatility and volume analysis.
Feature Engineering: 111 advanced features (moving averages, RSI, MACD, Bollinger Bands, volatility measures, lag features, cyclical encoding).
Feature Selection: SelectKBest with f_regression to retain 30 most predictive features.
Modeling: Trained & tuned 9 ML models; Ridge Regression outperformed all others.
Production Pipeline: Automated retraining, drift detection, and monitoring system.
Results
Metric	Ridge Regression
R² Score	0.9521
RMSE	0.000445
MAPE	6.04%
Accuracy	95.91%
git branch -M main
git push -u origin main)
