# numpy

statsmodel - Estimate Statistical models, and perform tests
scikit-image - collection of algorithms for image processing
scikit-learn - Simple and efficient tools for machine learning in python
pandas - Data analysis and manipulation
matplotlib - plotting library for 2d graphs and visualizations

np API list:

1. array - to create an array
2. zeros - with param as row and column creates m*n dimension array with zeros
3. ones - with param as row and column creates m*n dimension array with ones

dtype=np.int16 is the additional param to initialize the type of values in m*n array.

4. empty - with param as row and column creates m*n dimension array with zeros (empty array of size m*n)
5. eye - creates a square matrix with 1's along the diagonals and 0's other places.
6. arange - takes 3 args, starting(inclusive), ending(exclusive) and a step number,
	    can also take single argument to create array from 0 till that number
7. shape - to get the row and column size
8. reshape - row and column can be reshaped.
9. ones_like - you can pass any array of row and column size, it will create the same dimension array with ones as value.

PRINTING ARRAYS

asusual python print works.
pretty print --> set_printoptions(threshold = <<number>>)
number can be any number, to which the print wont summaize.
