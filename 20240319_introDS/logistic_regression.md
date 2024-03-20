# Logistic Regression
## What is logistic regression?
Logistic Regression uses statistical method to classify binary variable. Example of thhis type of regression problem includes spam detection, analyzing if client will click on an ad or not, calculating the survival rate on a perturbation, etc. Logisitic Regression predicts the probability of the occurance of a binary event. The dependent variable in logisitic regression follows a Bernoulli distribution and the estimation is done through Maximum Likelihood Estimate (MLE) approach.


## Problem formation
Logistic Regression uses the MLE as the likelihood maximization method to maximize the parameters that are most likely to produced the observed behavior. This is different than the Linear Regression which tries to minimize the distance between the regression line and the observed points.

The Logistic Regression has a sigmoid function, giving it a 'S' shaped curve to map the observed value between 0 and 1. We can use this curve to predict y, the dependent value such that if the output of the sigmoid function is > 0.5, then we classify the outcome as 1 or Yes, whereas if the output of the sigmoid function is <0.5, then we classify as 0 or No. 

## Type of Logistic Regression
The classification used in Logistic Regression can fall into the following type
- Binary Logistic Regression - There are two possible outcomes, eg., spam or not spam
- Multinomial Logistic Regression - The outcome has three or more nominal categories. An example of this is predicting the color of car the client will purchase.
- Ordinal Logistic Regression - The outcome has three or more ordinal categoryies. An example of this is rating your favorite colors from 1 to 10.

## Further reading and videos
- [Real Python tutorial](https://realpython.com/logistic-regression-python/) - Python tutorial on logistic regression
- [StatQuest Logistic Reggression](https://youtu.be/yIYKR4sgzI8?si=56UiVGyPW1npq9tD) - Video tutorial explaining concepts of Logistic Regresssion
