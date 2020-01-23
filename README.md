# ML_projects_
1. Supervised Learning 
    a. Linear Regression
    b. Classification: Perceptron Algorithms
       Basic idea of perceptron algorithm:
       In ML, the perceptron is an algorithm for supervised learning of binary  classifiers. This is a type of linear classifier, ie. a classification algorithm that makes its prediction based on a linear predictor function conbining a set of weights with the feature vector!
       High level implementation of Perceptron Algorithms with point (p,q)
           1. Try binary classification of a prediction : "y = step(w1x1 + w2x2 + b"
           2. If the point is correctly classified, do nothing
              If the point is classified positive, but it has a negative label, subtract learn_rate * p and learn_rate * q and learn_rate from w1, w2 and b respectively
              If the point is classified negative, but it has positive label, add learn_rate * p and learn_rate * q and learn_rate from w1, w2 and b respectively
           
    c. 
