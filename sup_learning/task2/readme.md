# Simple K-Nearest Neighbors (KNN) Classifier

A simple, from-scratch implementation of the KNN algorithm.

---

## Parameters

```python
"""
A simple implementation of the KNN algorithm.

Parameters:
    k               : how many neighbours to consider for predicting the label
    distance_metric : on what basis to find the nearest neighbors.
                      Supports "euclidean", "manhattan", "minkowski", "cosine"
    p               : p value required for minkowski distance. Pass 'np.inf' for L-infinity norm
    is_weighted     : Set to True if you want to implement weighted KNN
    normalization   : Whether to normalize the features or not. None for no normalization.
                      Supports "z-score" and "min-max"

Methods:
    train_test_split() : Splits data into training and testing sets based on a given ratio
    fit()              : Stores the input data for training
    predict()          : Predicts labels for a set of test points
    predict_one()      : Predicts the label for a single test point
    accuracy_checker() : Compares predicted labels with actual labels to calculate accuracy
"""
