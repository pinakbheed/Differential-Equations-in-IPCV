Assignment 1

Group Details:
Pinak Bheed (2557644)
Ganesh Murugan (2557687)
Pragya Pande (2561270)

Problem 3 Solution

sigma1 = 1.414
sigma2 = 2
time step size = 0.1 
iterations1 = 10
iterations2 = 20

images:
./ild
out10.pgm -> iterations1
out20.pgm -> iterations2

./gauss_conv
out10g.pgm -> sigma1
out20g.pgm -> sigma2

./difference
diff10.pgm -> out10.pgm and out10g.pgm
diff20.pgm -> out20.pgm and out20g.pgm

a)
The mean should remain same even after diffusion. The maximum should decrease and minimun should increase. The variance will decrease as diffusion proceeds. This goes with our results. 

As time step increases, the diffusion process is faster. For time step greater than 0.25 the diffusion process is unstable. Because it violates the max-min principle.

b)
The difference between the images computed from diffusion process and gaussian smoothing does not contain image structures. Therefore, they are similar.