# Decision & Regression Trees
## Introduction
### Decision trees 
Decision trees are a type of machine learning algorithm that are used for both classification and regression tasks. A decision tree is a model that predicts the value of a target variable by learning simple decision rules inferred from the data features. It's essentially a tree-like structure in which each internal node represents a feature or attribute, each branch represents a decision rule based on that feature, and each leaf node represents the outcome or prediction.
### Steps:
1. Start with a dataset and a target variable.
2. Choose the best feature to split the data based on a certain criterion, such as information gain or Gini impurity.
3. Create a node for that feature and split the data into subsets based on the possible values of that feature.
4. Repeat steps 2-3 recursively for each subset until a stopping condition is met, such as a maximum depth or a minimum number of samples per leaf.
5. Assign a prediction value to each leaf node based on the majority class or average value of the target variable in that subset.
### Regression trees 
Regression trees are a type of decision tree that are used for predicting continuous numerical values. They work in a similar way to decision trees, but instead of making binary decisions at each split, they split the data into two or more continuous regions based on a threshold value for a feature.
### Steps:
1. Start with a dataset and a target variable.
2. Choose the best feature and threshold to split the data based on a certain criterion, such as mean squared error or mean absolute error.
3. Create a node for that feature and threshold and split the data into subsets based on whether each sample falls below or above the threshold.
4. Repeat steps 2-3 recursively for each subset until a stopping condition is met, such as a maximum depth or a minimum number of samples per leaf.
5. Assign a prediction value to each leaf node based on the average value of the target variable in that subset.
## Datasets
* Fish: Decision tree
* House price: Regression tree
