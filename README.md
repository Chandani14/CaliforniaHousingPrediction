# CaliforniaHousingPrediction

The goal of this Project is to understand the logic, methods, and types available to implement
machine learning Regression Analysis.
Machine Learning Regression is a technique for investigating the relationship between independent
variables or features and a dependent variable or outcome. It’s used as a method for predictive modelling
in machine learning, in which an algorithm is used to predict continuous outcomes.
In this project, dealed with specific type of data input, real-estate, housing data. Specifically, tried to
build a predictive house pricing strategy for future house-for-sale purchases based on historical values.

The following steps, generating the ML Regressors, should be performed:
Pre-processed and clean the data of Caloifornia Hosuing.
Defined the Feature Variable ‘X’, and the Label/Target variable ‘y’. 
Spilted the data into training and test datasets used the 80/20 percent ratio.
Build a four Linear Regressor Model and fit it on the training dataset take its default parameters)
Evaluated the Regressor on the test dataset.
Performed Hyper Parmeter tunning for all regressor model.

### Four Regressor Model:
1. Ordinary Least Squares (OLS): Ordinary Least Squares (OLS) is a statistical method used in regression analysis to estimate the parameters of a linear regression model. OLS aims to minimize the sum of the squared residuals (the difference between the predicted and actual values) to determine the best-fit line for a given set of data.

    https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html

2. LASSO Regressor (L1):
LASSO (Least Absolute Shrinkage and Selection Operator) is a regularization technique used in linear regression to reduce the complexity of the model and prevent overfitting. LASSO adds a penalty term to the linear regression objective function, which imposes a constraint on the sum of the absolute values of the coefficients. The resulting regression model is called L1 regularization or LASSO regression.

   https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Lasso.html

3. Ridge Regressor (L2):
Ridge regression is a regularization technique used in linear regression to reduce the complexity of the model and prevent overfitting. Ridge regression adds a penalty term to the linear regression objective function, which imposes a constraint on the sum of the squared values of the coefficients. The resulting regression model is called L2 regularization or Ridge regression.

   https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Ridge.html

4. Elastic Regressor (L1 & L2):
Elastic Net regression is a regularization technique used in linear regression to reduce the complexity of the model and prevent overfitting. Elastic Net regression combines L1 and L2 regularization by adding a penalty term that is a weighted average of the sum of the absolute values of the coefficients (L1 penalty) and the sum of the squared values of the coefficients (L2 penalty)

    https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.ElasticNet.html
 
 ### Hyper Parameter Tunning of all Models.
 Performed HyperParameter tunning on four regressor model to choose one best model by taking their default parameters.
 
 ### Thank You.
