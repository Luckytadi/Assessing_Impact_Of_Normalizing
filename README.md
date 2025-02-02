# Assessing the Impact of Normalizing Numeric Data in Supervied Machine Learning

## Introduction

We learn that it is important to normalize numeric features for some machine learning algorithms.

Not normalizing numeric features has an adverse impact on the accuracy of the predictions, and on the number of iterations that the algorithm may take to converge on the optimum. This happens because the features with large absolute values dominate the calculations involved.

One particular algorithm which requires normalized numeric features is the k-Nearest Neighbours algorithm. This uses the Euclidean distance between training data and the test observation to find the closest neighbours. Features with large absolute values will dominate the calculation of the distance.

We assess the impact on accuracy of the kNN algorithm using the wine dataset.
