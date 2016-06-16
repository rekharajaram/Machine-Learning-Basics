# Machine-Learning-Basics

This project is a compilation of the algorithms for some of the Machine Learning models covered in Andrew Ng's Coursera Class on Machine Learning. I have used the datasets from the exercises in the class, and written the code in Python. This is a work in progress and I will continue to update the repository as I go through the exercises. Thanks!

Here's the list so far:

1. **Linear Regression Ex1**: A very simple linear regression model using Gradient Descent. The Cost Function is plotted as a function of number of iterations

2. **Logistic Regression Ex2**: A logistic regression model to plot the boundary between two classes of data (admitted vs not-admitted). A BFGS minimizer is used for the optimization (scipy.optimize.fmin_bfgs). I have calculated an F1 score of the training dataset and plotted the decision boundary to get a sense of how good the fit is.

3. **Logistic Regression One v Many Ex3**: Another logistic regression model, this time predicting the value (0-9) of hand-written digits. A classifier is built for each of the digits, and the digit with the highest 'probability' is the final predicted value. I used the L-BFGS-B minimizer for this algorithm (scipy.optimize.fmin_l_bfgs_b). The dataset (5000 digits represented as a 20x20 map - or 400 values) was split into a training and test set. I calculate an F1 score on the test set to get a sense of how well the algorithm is performing. Note that I used a 'macro' averaging for the F1 which gives the unweighted average of the F1 scores corresponding to all the classes


