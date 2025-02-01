# S&P 500 Stock Price Prediction using PySpark

This project demonstrates how to predict stock prices using historical data from the S&P 500 dataset. The project uses **PySpark** for data processing and machine learning.

## Dataset
The dataset used in this project is the **S&P 500 Stock Data** from Kaggle. It contains historical stock prices for all companies in the S&P 500 index, including:
- **Date**: The date of the stock price record.
- **Open**: The opening price of the stock.
- **High**: The highest price of the stock during the day.
- **Low**: The lowest price of the stock during the day.
- **Close**: The closing price of the stock.
- **Volume**: The number of shares traded.
- **Name**: The ticker symbol of the stock.

## Steps
1. **Load the Dataset**: The dataset is loaded into a PySpark DataFrame.
2. **Preprocessing**: Missing values are handled, and new features are created.
3. **Filter Data**: The dataset is filtered to focus on a specific stock (e.g., Apple).
4. **Split Data**: The data is split into training and testing sets.
5. **Feature Engineering**: Features are combined into a single vector for machine learning.
6. **Train a Model**: A Linear Regression model is trained on the training data.
7. **Evaluate the Model**: The model’s performance is evaluated using RMSE and R².
8. **Make Predictions**: The model is used to predict stock prices on the testing data.


## Requirements
- Python 3.x
- PySpark
- Jupyter Notebook (optional)
