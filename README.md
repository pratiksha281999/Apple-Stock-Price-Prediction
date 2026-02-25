# Apple-Stock-Price-Prediction

# Project Overview
This project focuses on building a Stock Price Prediction System using Machine Learning and Deep Learning techniques.
The goal is to analyze historical stock data, perform data preprocessing and feature engineering, and build predictive models to forecast future stock prices.

The project demonstrates:
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Scaling
- Time Series Data Preparation
- Model Building (LSTM / ML Models)
- Model Evaluation
- Visualization of Predictions vs Actual Prices

# Problem Statement
Stock prices are highly volatile and influenced by multiple factors.
This project aims to build a predictive model using historical stock data to forecast future closing prices and evaluate the model’s performance.

# Tech Stack
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- TensorFlow / Keras
- Jupyter Notebook

Multiple regression models were trained and evaluated, including Support Vector Machine (SVM), Random Forest, XGBoost, LightGBM, and a Long Short-Term Memory (LSTM) network. Model performance was compared using Root Mean Squared Error (RMSE):
- LSTM: 0.01
- Random Forest: 0.61
- XGBoost: 0.89
- SVM: 2.16
- LightGBM: 2.27
Among all models, the LSTM model significantly outperformed the others, achieving the lowest RMSE, demonstrating its superior ability to capture long-term dependencies and complex temporal patterns in stock price movements.
The final model was used to generate predictions for the next 10 trading days. The predicted values closely matched the actual stock prices, validating the model’s effectiveness and generalization capability.
This project highlights expertise in time-series forecasting, model benchmarking, deep learning architecture design, performance evaluation, and financial data analysis. It demonstrates the ability to compare multiple algorithms, select the optimal model based on quantitative metrics, and build a reliable predictive system using a structured machine learning workflow.
