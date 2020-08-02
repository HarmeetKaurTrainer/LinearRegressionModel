# Understanding Linear Regression Model
Linear regression is a linear model. Generally defined, if a model that assumes a linear relationship between the input variables (x) and the single output variable (y). Alternatively, y (always numerical) can be calculated from a linear combination of the input variables (x). hence, it can be easily said that linear regression is a linear approach to modeling the relationship between a scalar response (or dependent variable) and one or more explanatory variables (or independent variables).

The case of one explanatory variable is called a simple linear regression. When there is a single input variable (x), the method is referred to as simple linear regression. When there are multiple input variables, the method is referred as multiple linear regression.

In general, a model fits the data well if the differences between the observed values and the model's predicted values are small and unbiased. 
I am supremely intrigued by the power of a prediction model designed from a statistical approach combined with the power of python. I am just sharing a simple activity I conducted to understand the Linear Regression model based on the r2squared metric.

#R-squared; r2score

It is a statistical measure of how close the data are to the fitted regression line. It is the percentage of the response variable variation that is explained by a linear model. 

R-squared = Explained variation / Total variation

R-squared is always between 0 and 100%:

- 0% indicates that the model explains none of the variability of the response data around its mean.

- 100% indicates that the model explains all the variability of the response data around its mean.

In general, the higher the R-squared, the better the model fits your data. 

#LINEAR REGRESSION (2nd AUGUST, 2020)

#Problem Statement: 
You work in XYZ Corporation as a Machine Learning Engineer. The corporation wants you to build a system that can predict the salary of an employee based on the experience of the employee in number of years. 

You will be training the model and using the testing data/ random data (2D array) to check the efficacy of the prediction model.
