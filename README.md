# Gradient-descent-Perceptron
source files : (tme_etu.py and arftools.py)  the functions : - hinge(datax,datay,w), cost of the perceptron: hinge(x, y, w) = max(0, -y &lt; x.w >) - hinge_grad(datax,datay,w) its gradient. - mse(datax,datay,w), least squares cost - mse_g(datax,datay,w), least-squares cost gradient. These functions will return the mean of the error and the gradient over the datax dataset.  Functions take matrices as input: X ∈ R n,d, W ∈ R 1.d, Y ∈ R n,1  We check that the code works by plotting the surface of the error on a 2D example using the plot_error function provided.  The Linear class implements a gradient descent on the cost passed as an argument (the class will thus represent a perceptron if the hinge cost function is passed, a linear regression if the least squares cost function is passed). - We test on a simple example (type two Gaussian, use the gen_arti() function provided). - We plot the learning trajectory in the weight space and the boundaries obtained in the space of representation of the examples. - We modify our functions in order to allow the taking into account of a bias. - We modify our functions in order to allow a stochastic and/or mini-batch gradient descent.  USPS data: We test our algorithms on USPS data (handwritten numbers - choosing only two classes among the 10). We observe the value of the weights.   - On some examples of 2-class problems (6 vs 9, 1 vs 8 for example), we train our perceptron and visualize the weight matrix obtained without the bias. - We observe the weight matrix obtained when we train the perceptron with one class (6 per class). example) against all other classes. - Using the test data, the error curves in learning and testing are plotted as a function of the number of iterations.   2D data and projection: -We test our perceptron on the other artificial data provided (always with the function gen_arti().  - Coding a polynomial data projection function as seen in TD. Experiment and draw the boundaries. - Code a Gaussian projection function and experiment. Is it better to have a lot of points or few points for the projection base?  
