Exercise 1 - HMM illustrated
1. Use hmmlearn from scikit-learn (http://hmmlearn.readthedocs.io/en/latest/index.html)

2. Run the experiments in the tutorial and note the number of states, transition matrix / parameters, most likely state sequence. Visualize the samples.

Exercise 2 - HMM in a simple problem
Use hmmlearn to model the occasionally dishonest casino problem (slide 23):

a) construct the model assuming all parameters known.

b) train the model assuming the transition probability matrix is unknown.

c) train the model assuming the emission probability matrix is unknown.

d) train the model assuming both transition and emission matrices are unkonwn.

e) train the model assuming all the parameters unknown, including the number of states (suggestion: try with the number of states from 1 to 4 and compare the results of the score function).
