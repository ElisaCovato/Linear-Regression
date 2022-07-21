# Linear regression
A simple walkthrough to implement a linear regression model in Python.


## Overview
The Jupyter notebook [Linear Regression](https://github.com/ElisaCovato/Linear-Regression/blob/master/Linear%20Regression.ipynb) shows how to implement and plot a **simple linear regression** and a **multiple linear regression** (with 2 predictors) model.

### Regression model
For both regressions, we use the OLS function from [statsmodels](https://www.statsmodels.org/dev/generated/statsmodels.regression.linear_model.OLS.html), which fits a linear model using the _least squares approach_ (also called _Ordinary Least Squares_ ): this estimates the regression coefficients by  minimising the residual sum of squares (RSS).


### Dataset
Throughtout the notebook we will use the _advertsing_ dataset from "An Introduction To Statistical Learning" by James et al, which consist of the advertising budgets (in thousands of US dollars) for three media (TV, radio and newspapers) of a fictional company and sales data for that company. The idea is to implement a linear regression model to predict sales data, first by using one predictor (TV - simple linear regression), and then by using two predictors (TV and newspapers - multiple linear regression). 


### Plot
We will plot the resulting regression line and plane using Matplotlib libraries. 


___

## How to start
1. Check out that you have a working Python installation, preferably Python 3, and Jupyter installed
2. Git clone the [repo][https://github.com/ElisaCovato/Linear-Regression/] and cd inside directory
3. Install requirements: 

    `pip install -r requirements.txt`
4. Use the Jupyter notebook [Linear Regression](https://github.com/ElisaCovato/Linear-Regression/blob/master/Linear%20Regression.ipynb) to quickly implement a linear regression model
