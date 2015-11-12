Assignment 1

Group Details:
Pinak Bheed (2557644)
Ganesh Murugan (2557687)
Pragya Pande (2561270)

Problem 3 Solution

out1.pgm -> out1d.pgm
time step size = 0.1; 
iterations = 10;

c)

After performing difference the result needs to be shifted by 127.5 because the difference image lies between [-127.5, 127.5].
By shifting it, we do an affine transformation to the interval [0, 255].

In the optimal case the difference image should consist of just the noise. Linear diffusion filtering is not a very suitable method for
denoising as it removes important details from the image. This can be seen in the difference images calculated, which contains edges from
the original image. This is due to the fact that linear diffusion filtering doesn't care about edges. It simply smoothes the high frequent
details of the image.