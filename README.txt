Assignment 1

Group Details:
Pinak Bheed (2557644)
Ganesh Murugan (2557687)
Pragya Pande (2561270)

Problem 4 Solution

out1.pgm
lambda = 5
sigma = 1.5
timestep size = 0.2
no of iterations = 125

b)
Sigma is the gaussian smoothing applied to image before calculating the gradient. Increasing sigma increases the smoothness of image
before diffusion is applied. This leads to faster convergence to equilibrium state during diffusion.

Lambda is a contrast parameter. It is used to decide how to penalize the gradients based on the magnitudes of 
the gradient. This is used to preserve edges for longer diffusion times.

c)