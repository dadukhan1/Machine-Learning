# Unsupervised Learning with Scikit-learn

This project demonstrates the implementation of fundamental **Unsupervised Learning** techniques using synthetic datasets generated with Scikit-learn. It covers clustering, cluster evaluation, and dimensionality reduction through practical examples and visualizations.

## Topics Covered

* K-Means Clustering
* Elbow Method for Optimal K Selection
* DBSCAN (Density-Based Clustering)
* Principal Component Analysis (PCA)

## Datasets

Synthetic datasets generated using Scikit-learn:

* `make_blobs()` – for K-Means clustering and PCA
* `make_moons()` – for comparing K-Means and DBSCAN

## Workflow

### K-Means Clustering

1. Generate a synthetic dataset using `make_blobs()`.
2. Standardize the data using `StandardScaler`.
3. Find the optimal number of clusters using the Elbow Method.
4. Train the K-Means model.
5. Assign cluster labels using `fit_predict()`.
6. Visualize the resulting clusters.

### DBSCAN

1. Generate a non-linear dataset using `make_moons()`.
2. Scale the features.
3. Train the DBSCAN model.
4. Identify clusters and noise points.
5. Compare the clustering results with K-Means.

### Principal Component Analysis (PCA)

1. Generate a high-dimensional dataset.
2. Standardize the features.
3. Reduce the dimensions using PCA.
4. Transform the data into two principal components.
5. Visualize the reduced feature space.

## Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

## Learning Objectives

* Understand the fundamentals of Unsupervised Learning.
* Learn how K-Means groups similar data points.
* Use the Elbow Method to choose an appropriate number of clusters.
* Compare K-Means with DBSCAN on non-linear data.
* Apply PCA to reduce dimensionality while preserving important information.
* Visualize clustering and dimensionality reduction results.
