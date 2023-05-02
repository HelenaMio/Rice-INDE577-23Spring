# Principal Component Analysis
## Introduction 

Principal Component Analysis (PCA) is a widely used unsupervised machine learning technique for data analysis and dimensionality reduction. It is a powerful tool for understanding the underlying structure of complex data sets by identifying the most important features or patterns.

PCA works by finding the directions (or principal components) that explain the maximum amount of variance in the data. These principal components are orthogonal to each other and provide a new coordinate system for the data. By projecting the original data onto these principal components, we can reduce the dimensionality of the data while retaining most of the important information.

## Algorithm Steps

The PCA algorithm can be summarized in the following steps:

1. Standardize the data: Subtract the mean and divide by the standard deviation of each feature.
2. Calculate the covariance matrix: Compute the covariance matrix of the standardized data.
3. Calculate the eigenvectors and eigenvalues of the covariance matrix: Eigenvectors are the principal components, and eigenvalues represent the amount of variance explained by each principal component.
4. Sort the eigenvectors by their corresponding eigenvalues in descending order.
5. Select the top k eigenvectors: Choose the top k eigenvectors that explain the most variance in the data.
6. Project the data onto the new coordinate system: Multiply the standardized data by the selected eigenvectors to obtain the new lower-dimensional representation.

## Data Resource
Fish dataset is used to show the scatter plot based on species feature.
