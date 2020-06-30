# Machine_Learning_Algorithms
Conditional probability and Bayes' Theorem

Linear Regression:
Linear regression is an algorithm which helps us to solve Supervised Machine Learning problem. Supervised Machine Learning can be subdivided into two categories: 1. Regression 2. Classification. If the output is numerical then we use Regression algorithm. In this kind of algorithm the model may not give accurate result for the training dataset but in test dataset the accuracy will be high. This is called Bias Vraiance Trade off.
Here, in the training data we had two numerical columns: Experience and Salary. We drew a scatter plot and Best Fit line for the plot. To draw the best fit line we need to vary the slope(m) and intercept(b) for which Sum of Squared Residual is minimum(i.e, the summation of the square of the distance between the line and all the points should be minimum.)
This can be done by two methods: 1. Ordinary Least Squares {Statistics domain} 2.Gradient Descent{Calculus family}. Here, we have used Ordinary Least Squares Regression.
The slope m is calculated using the formula m=(sum((X-Xbar)*(Y-Ybar))/sum((X-Xbar)**2)) where Xbar is mean value of X and X indicates every X value. The intercept b is calculated using the formula b=Ybar-(m*Xbar). So, the eqn of the best fit line becomes y1=m*X+b. Here, we have created a class with the name of LinearRegression, and also added 2 methods in it:

1. The fit method, which will be used to train our model.

2. The predict method, which will do the prediction
For a particular value of X(Experience) our model predicts the probable Salary(Y).
