# META-Stock-Prediction-Python-ML
Stock price prediction is one of the most challenging tasks in financial markets due to the volatile and highly non-linear nature of stock movements. Investors and traders rely on accurate predictions to make informed decisions, but stock prices are influenced by numerous factors, including both company-specific variables and broader economic conditions.

My goal is to explore whether machine learning techniques can effectively model these relationships and outperform simpler baseline models in predicting stock returns, especially in the case of META.


Several machine learning models, including Random Forest, XGBoost, and SVM, will be implemented based on stock data, technical indicators (e.g., RSI, MACD) and macroeconomic factors (e.g., interest rates, S&P 500 returns) to determine which approach yields the most accurate predictions, providing valuable insights for investors.


The dataset used for this project was sourced from the ‘yfinance’ Python library and the FRED API.


The project concludes that the tuned SVM model with a polynomial kernel (degree 2) demonstrated the best performance because of its ability to capture non-linear relationships between stock returns and features. The SVM model not only performed well on the training and validation sets but also generalized effectively to the test set, as indicated by minimal overfitting. This is critical for any financial prediction model, as overfitting historical data often results in poor future predictions.
