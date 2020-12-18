# Abalone Fishing Status
### SVM classification (Support Vector Machines)

This project uses data from the UCI Machine Learning Repository on abalone fish to make a binary prediction on fish age (0-10 yrs, 11+ yrs).  The UCI repository suggests using this dataset to predicting age directly, but we apply a practical use case for building a binary classifier on fish age.
The data can be found and downloaded here: 
- https://archive.ics.uci.edu/ml/machine-learning-databases/abalone/abalone.data

For this project, we download directly from a link made available through University of Washington (https://library.startlearninglabs.uw.edu/DATASCI420/2019/Datasets/Abalone.csv).

#### Problem Description

Fisherman may only fish abalone that are at least 11 years old, but determining abalone age is a very cumbersome process that requires a microscope.  A predictive classifier based on easily observable characteristics would be much more efficient in sorting the abalone.  Such a process could have implications on fishing regulations and their adherence.

The dataset that we use to build and test our model contains several features on the physical characteristics of abalone, including their age (as measured by the number of rings on their shell).  We have \~4,200 abalone samples and binarize the ring count as our target variable.   We build and tune an SVM classifier to make our predictions.
