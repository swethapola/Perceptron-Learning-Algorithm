# Perceptron-Learning-Algorithm
We are going to implement the perceptron algorithm on a very simple feature spaces: pixels in images of handwritten digits. To do this, we have provided a function to read image files (load_image_files) of a given digit (n), from a provided path (path=...), convert them to a numpy matrix, and finally flatten that numpy matrix into a vector. The function load_image_files returns all of the vectors corresponding to pixels in handwritten digits of n from the MNIST dataset. Note that the original images were 28x28 pixels, this function returns “images” of 28x28=784 zeroes and ones, corresponding to whether the image was white or black at a given location, but each “image” is a single vector of length 784 (to make things easier for you)
