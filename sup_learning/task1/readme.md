# Simple Decision Tree Classifier

A simple, from-scratch implementation of the Decision Tree Classifier Algorithm.

---

## Parameters

```python
"""
A simple implementation of Decision Tree Classifier.

Parameters:
    function    : What method to use to calculate impurity. Supports "gini" and "entropy"
    max_depth   : Maximum allowed depth of tree
    min_samples : Minimum number of samples required at a node to make a split

Methods (for user):
    fit()         : Learn the tree structure from training data
    predict()     : Predict the labels for a list of input points
    predict_one() : Predict the label for a single point
    plot_tree()   : Visualize the trained decision tree
"""
