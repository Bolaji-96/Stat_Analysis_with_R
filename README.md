Statistical Analysis with R

### Background
Our client would like to understand the following:
* The effect of **Dividend** on Scale Stock return by creating a linear regression model
*  The effect of **all input variables** on scaled Stock return by creating a multivariate regression model. 
*  Compute and state the basic statistics
*  Create and show a fully labeled Histogram of the Target variable
*  Conduct a T-test that the mean for “stock_return_scaled” is equal to 300
*  Perform a simple linear regression using dividend as the independent variable and
stock_return_scaled as the dependent variable
*  Perform a multiple linear regression on all variables and report the results

## Methodology 
* Assess data
* Exploraatory Data Analysis
* Conduct T-test
* Linear Regression
* Multiple Linear Regression
* Model Evaluation

## Analysis Conclusion
- The mean average is **not** equals 300
- There is a relationship between dividend and stock returns due to low p-value, but with an r-square value 0f **0.04%**, it holds a very low predictive power. Dividend causes a -**5.118** in stock return. 
- The multiple linear regression reliability was affected by the introduction of more independent variables. Some variables were removed based on the high p-values. Even though the reliability of model was affected, the p-value still suggests that the model is statistically significant. 
