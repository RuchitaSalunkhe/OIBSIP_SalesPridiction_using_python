# OIBSIP_SalesPridiction_using_python
# Sales Prediction using Linear Regression

## Overview
Sales Prediction using Linear Regression is a machine learning project that aims to predict future sales based on advertising expenses in different channels, including TV, Radio, and Newspaper. The project uses historical data from the 'Advertising.csv' file to train a Linear Regression model and make predictions.

## Prerequisites
- Python 3
- pandas
- scikit-learn
- matplotlib
- seaborn

## Installation
1. Install the required libraries by running:
```bash
pip install pandas scikit-learn matplotlib seaborn
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.metrics import mean_squared_error, r2_score
```

## Steps
1. Place your dataset in CSV format with the following columns: 'TV', 'Radio', 'Newspaper', and 'Sales'.
2. Update the `data_file` variable in the code to point to your dataset file.
3. Run the Python code `sales_prediction.py`.
4. The code will split the data into training and testing sets, train the Linear Regression model, and make predictions.
5. It will then print the Mean Squared Error (MSE) and R-squared (R2) values to evaluate the model's performance.
6. The scatter plots of advertising expenses vs. sales will also be displayed for visualization.
7. To predict future sales based on new advertising expenses, update the values of `new_TV`, `new_Radio`, and `new_Newspaper` in the script and run it again.



