Run the example in section 3.3. of the following tutorial (https://machinelearningmastery.com/tensorflow-tutorial-deep-learning-with-tf-keras/). 

Do the following exercises:

Use a 6 month training window and compare it with the reference model.
Improve the previous model and analyze the learning curves to check the model convergence. Suggestion: consider using normalization of data (see the note below for further reading), dropout, batch normalization, early stopping. The tutorial only splits the data into train and test sets. To properly evaluate these options, you need to split the data into train, validation, and test sets (see the note below section "split the data").
Repeat the above experiment with a training window of 12 months.
The model from the tutorial is a single-step model (it tries to predict the following time point, one month to the future). Try to do a multi-step model with a 6 months training window and predict the next 3 months (in the future).
In each case do not forget to run 5 times and register the average and standard deviation of the performance metrics used.
