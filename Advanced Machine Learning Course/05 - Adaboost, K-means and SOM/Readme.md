Exercise 1 - AdaBoost
0) download the data set Breast Cancer Wisconsin (Original) in http://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Original%29

1. use a regression model to classify (logistic regression) and record the accuracy

2. use AdaBoost with 7 logistic regression base learner experts and compare results

3. compare with other numbers of experts (ex. 3, 10)

4. repeat 2 and 3 with decision tree base learner experts

Suggestion: scikit-learn has the LogisticRegression classifier and the AdaBoostClassifier class.

Exercise 2 - K-means and SOM
0. download the Iris data set https://archive.ics.uci.edu/ml/datasets/iris

1. apply K-means to this data set, with K=3. Obtain the confusion matrix between cluster labels and true classes, and compute the accuracy.

2. similar to the previous point, apply Gaussian mixture model to this data set

3. compare with SOM results (suggestion: use a map size of 20)

Note: sompy function som.clusters(...) produces the cluster labels of each neuron in k-means style, and som._bmu[...] obtains the labels of the data points through the best matching unit.
