# k-Means Clustering
## Introduction

K-Means is a type of partitioning clustering, that is, division of objects into clusters such that each object lies in exactly one cluster. It is a method of vector quantization, originally from signal processing, that aims to partition n observations into k clusters in which each observation belongs to the cluster with the nearest mean (cluster centers or cluster centroid), serving as a prototype of the cluster.

![k-means image](https://upload.wikimedia.org/wikipedia/commons/e/ea/K-means_convergence.gif)

## Steps

The procedure follows a simple and easy way to classify a given data set through a certain number of clusters (assume k clusters). The main idea is to define k centroids, one for each cluster.

The main steps are:

1. **Initialization**: Randomly initialize K cluster centroids.
2. **Assignment step**: Assign each example to the closest cluster centroid.
3. **Move centroid step**: Compute the new centroid (mean) of each cluster.

## Data
Iris data comes from Kaggle, which consists of 50 samples from each of three species of Iris (Iris setosa, Iris virginica and Iris versicolor). Four features were measured from each sample: the length and the width of the sepals and petals, in centimeters. Based on the combination of these four features, Fisher developed a linear discriminant model to distinguish the species from each other.
