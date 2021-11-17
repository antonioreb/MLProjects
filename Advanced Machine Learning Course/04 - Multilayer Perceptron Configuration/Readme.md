Exercise on MLP configuration
Do the following exercises using scikit-learn.

Compare the performance of two MLP learning the XOR problem:

1. MLP with 2 inputs, 2 hidden neurons and 1 output neuron with complete forward connections;
2. MLP with 2 inputs, 1 hidden neuron, 1 output neuron and shortcut connections (same configuration as in 1st class) - you may use JavaNNS for this configuration, or other software package that allows custom NN topologies,
in the following situations:

A) Hidden neurons with logistic activation function
Data set with binary values in {0, 1}
Standard backpropagation algorithm

B) Hidden neurons with hyperbolic tangent activation function
Data set with binary values in {-1, 1}
Backpropagation with momentum algorithm

C) Hidden neurons with relu activation function
Data set with binary values in {0, 1}
Standard backpropagation algorithm

D) Hidden neurons with relu activation function
Data set with binary values in {0, 1}
Backpropagation with momentum algorithm

Note that, in scikit-learn the only solver that allows controlling the momentum parameter is SGD.

Note the average and standard deviation of the learning cycles until convergence in both situations. You may use in the order of 5 runs for these statistics.
