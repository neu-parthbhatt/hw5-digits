# HW5-digits

1. The support is problematic since we are facing class imbalance. A way to solve this is to have stratified split between the classes, for a better accuracy. Please find below the confusion matrix from stratified split of data.

## Question 2

Use a decision tree classifier with the same data. 
Investigate model performance using a validation curve. 
Comment briefly on the results (including comparison with results above).

## Question 3

In [5.08 Random Forests](https://github.com/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/05.08-Random-Forests.ipynb), VanderPlas performs digits classification with a random forest. 
He uses `n_estimators=1000`. 
Use a validation curve to investigate the choice of n_estimators.
Comment briefly on the results (including comparison with results above).

## Question 4

Investigate use of 
[AdaBoost](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.AdaBoostClassifier.html).
Look at the scikit-learn
[adaboost example](https://scikit-learn.org/stable/auto_examples/ensemble/plot_adaboost_hastie_10_2.html) for ideas.
Boosting is discussed in Section 8.2.2 (p345) if ISLR2. 
Comment briefly on results and your choice of hyperparameters (including comparison with results above).

## Question 5

Adapted the use of SVC in cells 18-26 of [Labeled Faces in the Wild demo](https://github.com/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/05.07-Support-Vector-Machines.ipynb) in VanderPlas.
When selecting optimal hyperparameters, make sure that your range encompasses the minimum.
Comment briefly on results and your choice of hyperparameters (including comparison with results above).
