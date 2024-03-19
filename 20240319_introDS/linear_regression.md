# Linear Regression
## What is linear regression?
Linear Regression uses statistical method to analyze the relationship between a dependent variable and one or more independent variables. For example you can observe the relation between housing prices and how it depends on certain features such as square footage, location, number of bedrooms and bathrooms, etc. The independent features of each house represents an observation and the price depends on one or more of the features. The goal of linear regression is to create a model that can predict the dependent variable based on independent variables, in this case the features of the house that predicts the price of the home.

In linear regression problems the input are continous, whereas in logistic regression it is binary (more on that later).


## Problem formation
To implement linear regression we have dependent variable _y_ on set of independent variables _x = (x<sub>1</sub>,...,x<sub>r</sub>)_ where _r_ is number of predictors. The linear relationship between y and x is _y=&beta;<sub>0</sub> + &beta;<sub>1</sub>x<sub>1</sub>+...+&beta;<sub>1</sub>x<sub>r</sub>r+&epsilon;_ where &beta;<sub>0</sub>, &beta;<sub>1</sub>, ..., &beta;<sub>r</sub> are the regression coefficients and &epsilon; is the random error.

Linear regression calculates the predicted weights (_b_<sub>0</sub>, _b_<sub>2</sub>, ..., _b_<sub>r</sub>). These weight are estimators of the regression coefficient and define the estimated regression function _f_(x) = _b_<sub>0</sub> + _b_<sub>2</sub>+ ... + _b_<sub>r</sub>. The estimated response is the predicted response _f_(x<sub>i</sub>) for each observation. The differences between the actual response y(<sub>i</sub>) and estimated reponse are call residuals. 

The goal is Linear regression is to determine the best predicted weights which correspond to the smallest residuals. To get the best weight, we want to minimize the sum of squared residuals for all observations _i_. This method is called ordinary least squares and can be written as \sum_{<sub>i</sub>(y<sub>i</sub> - f(x<sub>i</sub>))^i{2}}.
