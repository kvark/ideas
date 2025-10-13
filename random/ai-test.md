Artificial Intelligence today is very similar to compression. It finds correlations in the input data and exploits them to reduce the volume of internal circuity representing the body of training data.

Here is an ultimate test for an AI system:
  - we take billions of point samples, training on the function that is: number of steps before this point flies away following Mandelbrot equation
  - we train the network to reproduce this number
  - we aggressively distill the network into smaller and smaller ones
  - in the end, we expect the circuity to approximate the Mandelbrot loop
