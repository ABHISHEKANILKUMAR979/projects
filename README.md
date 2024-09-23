# projects

iris dataset - unsupervised learning

[LINK](https://docs.google.com/document/d/1pHMP9ChXrXMalqOzkB4P0lz0RVAT3jKPIuy96CqlRYs/edit#heading=h.iic74dldoib4)


Description:

This project demonstrates the application of unsupervised machine learning techniques, specifically KMeans and Hierarchical clustering, to the Iris dataset. The goal is to group similar Iris flowers based on their sepal and petal measurements without prior knowledge of their species.

Key Steps:

Data Loading and Preprocessing: The Iris dataset is loaded from the scikit-learn library and the species column is dropped, as it's the target variable in a supervised classification problem.
KMeans Clustering:
The KMeans algorithm is applied with 3 clusters, corresponding to the known number of Iris species.
The algorithm iteratively assigns data points to the nearest cluster centroid and recalculates centroids until convergence.   
The resulting clusters are visualized to assess their separation.
Hierarchical Clustering:
Hierarchical clustering is performed using the agglomerative approach with Ward's linkage.
The algorithm starts with each data point as a separate cluster and merges them based on similarity until the desired number of clusters is reached.
The clusters are visualized to observe the hierarchical structure.
Purpose:

This project serves as an educational resource for understanding clustering techniques and their application to real-world data. It provides a hands-on example of how to implement and evaluate clustering algorithms.
