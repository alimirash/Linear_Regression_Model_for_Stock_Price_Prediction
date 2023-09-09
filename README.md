# Linear Regression Model for Stock Price Prediction

![GitHub repo size](https://img.shields.io/github/repo-size/alimirash/Linear_Regression_Model_for_Stock_Price_Prediction)
![GitHub contributors](https://img.shields.io/github/contributors/alimirash/Linear_Regression_Model_for_Stock_Price_Prediction)
![GitHub stars](https://img.shields.io/github/stars/alimirash/Linear_Regression_Model_for_Stock_Price_Prediction?style=social)
![GitHub forks](https://img.shields.io/github/forks/alimirash/Linear_Regression_Model_for_Stock_Price_Prediction?style=social)

## Overview

This repository contains a Python script for a linear regression model used to predict stock prices, specifically focusing on EURUSD (Euro to US Dollar) historical data. The model uses the scikit-learn library for linear regression and provides predictions based on the opening prices.

## Dataset

The dataset used in this project is sourced from the following URL:
[EURUSD_M1.csv](https://github.com/alimirash/Linear_Regression_Model_for_Stock_Price_Prediction/blob/041953ceed62ef291554e47c3cd6acd628109b26/EURUSD_M1.csv)

The dataset includes the following columns:
- Date
- Open
- High
- Low
- Close
- Volume

## Requirements

Before running the code, ensure you have the following Python libraries installed:

- pandas
- numpy
- matplotlib
- scikit-learn

You can install these libraries using pip:

```bash
pip install pandas numpy matplotlib scikit-learn
```

## Results

The model predictions are plotted against the actual closing prices, providing visual insights into the prediction accuracy.

### Plot 1: Historical Data for All Available Data Points

To provide a comprehensive view of the historical data, the following plot shows the entire dataset's historical closing prices. This can help you understand the broader trends in the data.

![Historical Data for All Available Data Points](https://github.com/alimirash/Linear_Regression_Model_for_Stock_Price_Prediction/blob/d48a3f06bb087112a8dafc7a928cd1c0fb36a68b/Plots/History.png)
### Plot 2: Close Prices in EURUSD

This plot displays the close prices in EURUSD, including the last 200 data points.

![Close Prices in EURUSD](https://github.com/alimirash/Linear_Regression_Model_for_Stock_Price_Prediction/blob/d48a3f06bb087112a8dafc7a928cd1c0fb36a68b/Plots/LinearRegression_Result.png)
