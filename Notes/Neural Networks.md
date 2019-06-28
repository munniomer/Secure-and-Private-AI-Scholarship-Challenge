# Neural Networks
Chapter Notes for lesson 2, Introduction to Neural Networks

Neural networks vaguely mimic the way the brain operates, with neurons that fire bits of information.

Deep neural networks have a greater number of hidden layers , and consequently more nodes, ore edges, and more information entering and leaving the cells.

One kind of problem that neural networks are used to solve is **classification** involving in the case of binary, something as simple as acceptance, or rejection.

**Binary classification** involves the identification of a linear boundary to demarcate selected vs rejected cases. This prediction is made on the basis of a linear equation of the form **w<sub>1</sub>x<sub>1</sub> + w<sub>2</sub>x<sub>2</sub> + b = 0.** This is represented in vector notation as **Wx + b = 0**, where W = (w<sub>1</sub>, w<sub>2</sub>), x=(x<sub>1</sub>, x<sub>2</sub> representing the weights and points of input respectively. (**W** and **x** are two vectors whose product is being taken.

y, being what we're trying to predict is called the label, and in the case of binary classification can take values such as 0 or 1.

Predictions ca be of the form

        {   1, if Wx + b >= 0
ŷ   =   
            0, if Wx + b < 0    }
            

Our predicted models can also be of higher dimensions, in which case the boundzry will be in the form  
    w<sub>1</sub>x<sub>1</sub> + w<sub>2</sub>x<sub>2</sub> + ... + w<sub>n</sub>x<sub>n</sub> + b = 0
for an n-1 dimensional hyperplane.
    
This equation, as before, can be abbreviated in the form of **Wx + b = 0**, and the prediction for the same will be same as listed above.

### Perceptron

Perceptrons are the building blocks of neural networks. They encode our equations in the form of a graph in the manner described below.

* Data and boundary line get fitted inside node.

* Small nodes are added for input.

* The perceptron then plots the points and checks if they are in positive or negative area.

* If the point is in positive area, yes is returned, otherwise, no is returned.

