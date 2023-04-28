
# Tutorial 7 

### Implement Gradient Descent for Linear Regression


Gradient Descent is an iterative optimization algorithm used for finding the minimum of a function. In Linear Regression, Gradient Descent can be used to find the parameters that minimize the mean squared error (MSE) between the predicted and actual values of the target variable.

The basic steps for implementing Gradient Descent for Linear Regression are:

1. Initialize the parameters to zero or small random values
2. Compute the predicted values using the current parameters
3. Compute the gradients of the MSE with respect to the parameters
4. Update the parameters using the gradients and the learning rate
5. Repeat steps 2-4 until convergence or a maximum number of iterations is reached

The learning rate controls how large the step is taken in the direction of the gradients. A small learning rate can lead to slow convergence, while a large learning rate can cause the algorithm to overshoot the minimum and diverge. A good starting point for the learning rate is 0.01, and it can be adjusted based on the performance on the training data.

By minimizing the MSE, Gradient Descent finds the best linear relationship between the input features and the target variable. Once the parameters are learned, they can be used to make predictions on new input data.



## Authors

- [@Unicorn](https://www.github.com/sahilgoyal7214)

