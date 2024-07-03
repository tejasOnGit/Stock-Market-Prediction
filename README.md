## Financial Time Series Analysis and Prediction
## Introduction
This project conducts a comparative analysis of multiple machine learning models for forecasting the closing value of stocks, with a focus on the "Close" column.
---
# Financial Time Series Analysis and Prediction

This project focuses on the analysis and prediction of financial time series data using various machine learning and deep learning techniques. The dataset used in this project consists of historical index data, including open, high, low, and close prices, adjusted close prices, and volume.

## Overview

The project involves several stages:

1. **Data Exploration and Cleaning:**
   - Exploring the dataset to understand its structure and summary statistics.
   - Cleaning the data by handling missing values, and outliers, and removing duplicates.

2. **Feature Engineering:**
   - Extracting time-based features from the date column.
   - Creating lagged features and computing technical indicators like moving averages, RSI, and Bollinger Bands.

3. **Data Visualization:**
   - Generating histograms and boxplots to visualize the distribution of numerical columns and identify outliers.

4. **Modeling and Prediction:**
   - Performing feature selection using SelectKBest with F-regression.
   - Implementing various regression models including Linear Regression, Lasso Regression, Ridge Regression, Gradient Boosting, and RNN (LSTM).
   - Evaluating models based on Mean Squared Error (MSE) and R-squared.

## Topics Covered

- Exploratory Data Analysis (EDA)
- Data Cleaning Techniques
- Feature Engineering in Time Series Data
- Univariate Feature Selection
- Implementing Regression Models:
  - Linear Regression
  - Lasso Regression
  - Ridge Regression
  - Gradient Boosting
- Deep Learning for Time Series Forecasting:
  - Recurrent Neural Networks (RNN) using LSTM
- Model Evaluation and Comparison

## Installation

To run this project locally, make sure you have Python 3.x installed along with the required libraries listed in `requirements.txt`. You can install them using pip:

```bash
pip install -r requirements.txt
```

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/financial-time-series-analysis.git
   cd financial-time-series-analysis
   ```

2. Run the Jupyter Notebook `Financial_Time_Series_Analysis.ipynb` to explore the dataset, perform data cleaning, feature engineering, and train different models.

3. Modify the notebook or add more features/models as per your requirements.

## Dependencies

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- tensorflow (for LSTM model)

## Contributors

- Tejas Rajput (@tejasOnGit)

Feel free to fork this repository and contribute to it!

---
```bash
pip install -r requirements.txt

