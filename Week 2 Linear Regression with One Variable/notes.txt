# Model and Cost Function

## Cost Function
We can measure the accuracy of our hypothesis function by using a cost function. This takes an average difference (actually a fancier version of an average) of all the results of the hypothesis with inputs from x's and the actual output y's.

This function is otherwise called the "Squared error function", or "Mean squared error". 

## Cost Function - Intuition II
A contour plot is a graph that contains many contour lines. A contour line of a two variable function has a constant value at all points of the same line.


#Parameter Learning

## Gradient descent
We gradient descent to estimate the parameters in the hypothesis function.
The cost resulting from selecting a particular set of parameters for hypothesis.

## Learning rate:  α
A smaller α would result in a smaller step and a larger α results in a larger step. We should adjust our parameter α to ensure that the gradient descent algorithm converges in a reasonable time.


## Note
* At each iteration, one should simultaneously update the parameters in the hypothesis function.

* Gradient descent can converge to a local minimum, even with the learning rate α fixed. As we approach a local minimum, gradient descent will automatically take smaller steps. So, no need to decrease α over time.



