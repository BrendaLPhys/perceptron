# Perceptron

#### A perceptron attempt for a linear classifier, here are some resources I found to be very useful:

- [This video is really easy to understand](https://www.youtube.com/watch?v=4Gac5I64LM4&t=688s&ab_channel=ritvikmath)
- [And this one saved me!](https://www.youtube.com/watch?v=OVHc-7GYRo4&ab_channel=BrianFaure)
- [More detailed explanations 1](https://www.python-course.eu/dividing_lines_between_classes.php)
- [More detailed explanations 2](https://www.python-course.eu/simple_neural_network.php)
- [A very nice example](https://www.askpython.com/python/examples/single-perceptron-neural-network)
- [Neural network from scratch](https://jtsulliv.github.io/perceptron/)

## Discussion:

### What is the optimal number of iterations? 

Based on the learning algorithm here the ideal accuracy is reached by the 4th iteration.
Although there's also this [thing](https://leimao.github.io/blog/Perceptron-Convergence-Theorem/). 
The convergence theorem states that the algorithm will for sure find a solution when the data
is linearly separable, not only that but the amount of iterations  or steps needed can be obtained 
with R^2/d^2 where R is a certain constant and d the distance of the closest datapoint to the linear
separate line or plane or hyperplane. 

[Perceptron Convergence Theorem in page 7](http://web.mit.edu/course/other/i2course/www/vision_and_learning/perceptron_notes.pdf)

### How many solutions can the perceptron find for this binary separation problem?

If we think of the algebraic expression that we are solving and if we look at the plots we
obtain, there is an infinite number of solutions, or we can see an infinite amount of lines
that could fit in a space where they are still correctly separating (classifying) the two
groups of data points. [This is a useful resource to check it out](http://hagan.okstate.edu/4_Perceptron.pdf).
