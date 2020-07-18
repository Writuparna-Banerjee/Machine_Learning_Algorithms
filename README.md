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




# Implementation of Logistic Regression from Scratch

Logistic Regression is a classification technique in Supervised Machine Learning. It's similar to Linear Regression. To find a hyperplane that best classify the given input, the following is calculated: argmax np.sum(y*np.dot(X,w.T). However, to remove outliers the Cost (sigmoid) function is used.For,binary classification it is considered that if the value of sigmoid function is greater than 0.5, then the target variable y is 1 else it is zero.
Here, we have implemented the Algorithm from scratch in Python i.e., without using Scikit-Learn or any other Machine Learning Toolbox. The dataset contains marks obtained by students in 2 exams as features and the target label, 0/1 as whether they will be admitted to the university (1) or not (0).

Reference taken from: https://web.stanford.edu/~jurafsky/slp3/5.pdf




