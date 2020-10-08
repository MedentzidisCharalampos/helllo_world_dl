# helllo_world_dl

The problem:

We have a set of numbers and try to find the patterns between them.

The data:

Here are the numbers: 

X = [-1, 0, 1, 2, 3, 4]
Y = [-3, -1, 1, 3, 5, 7]

There is a formula that maps X to Y: Y = 2 * X -1

This is the hello world in deep learning. We will try to solve the problem of finding the function that connects two datasets. Given 6 points of x and y  we will estimate the function y=f(x)

The architecture of the model:

A Fully Connected Layer  with 1-unit and input one value.  

The model is compileds with Squared Mean Error as loss function Stochastic Gradient Descent as optimizer.  
The model is trained for 500 epochs. It predicts Y value for X = 10 and the result is 18.98.  
