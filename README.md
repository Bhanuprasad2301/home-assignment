Name:Bhanu prasad 
id:700762758

This demonstrates linear regression using two methods: the closed-form solution and gradient descent. It first generates 200 random data points with x uniformly sampled between 0 and 5, and y calculated as y = 3 + 4x + noise, where noise is normally distributed.

Using the normal equation, it computes the optimal regression line, giving an intercept =3.1052 and slope = 3.9844. Then, it uses a custom gradient_descent function with a learning rate of 0.05 and 1000 iterations to iteratively find the parameters, which converge to nearly identical values

The code also tracks the mean squared error (MSE) over time, ending with a very low error = 0.9338, confirming that the model fits the data well. Finally, it plots the dataset along with both regression lines and shows the loss curve, visually demonstrating how gradient descent reduces error until convergence.

This project is a hands-on illustration of how linear regression works both analytically and numerically, and it highlights that both approaches lead to the same solution when implemented correctly.



