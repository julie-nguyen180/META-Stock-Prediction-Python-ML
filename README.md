# META-Stock-Prediction-Python-ML
Stock price prediction is one of the most challenging tasks in financial markets due to the volatile and highly non-linear nature of stock movements. Investors and traders rely on accurate predictions to make informed decisions, but stock prices are influenced by numerous factors, including both company-specific variables and broader economic conditions.
My goal is to explore whether machine learning techniques can effectively model these relationships and outperform simpler baseline models in predicting stock returns, especially with the case of META.

Several machine learning models, including Random Forest, XGBoost, and SVM, will be implemented based on stock data, technical indicators (e.g., RSI, MACD) and macroeconomic factors (e.g., interest rates, S&P 500 returns) to determine which approach yields the most accurate predictions, providing valuable insights for investors.

The dataset used for this project was sourced from the ‘yfinance’ Python library and the FRED API.
•	‘yfinance’ is an open-source tool for research and educational purposes that uses Yahoo Finance's publicly available APIs with a rich and reliable source of financial market data. Stock price data (‘Close’) for META and the S&P 500 index (stock performance of 500 of the largest companies listed on stock exchanges in the U.S.) were retrieved from this.
•	The FRED® API is a web service that allows developers to write programs and build applications that retrieve economic data from the FRED® and ALFRED® websites hosted by the Economic Research Division of the Federal Reserve Bank of St. Louis. The Federal Funds rate, a proxy for interest rates, was obtained from the FRED API.
