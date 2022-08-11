# PCA_and_Clustering_for_Wine_Dataset
Perform Principal Component Analysis (PCA) and perform clustering using first 3 principal component scores (Both Heirarchial and KMeans clustering-Scree Plot or Elbow Curve. Obtain the optimum number of clusters and check whether we have obtained same number of clusters with the original data (Class column we have ignored at the begining who shows it has 3 clusters) df

Perform Principal component analysis (PCA) and clustering:

Clustering analysis is an unsupervised learning method that separates the data points into several specific bunches or groups, such that the data points in the same groups have similar properties and data points in different groups have different properties in some sense.
It comprises of many different methods based on different distance measures. E.g. K-Means (distance between points), Affinity propagation (graph distance), Mean-shift (distance between points), DBSCAN (distance between nearest points), Gaussian mixtures (Mahalanobis distance to centers), Spectral clustering (graph distance), etc.
Centrally, all clustering methods use the same approach i.e. first we calculate similarities and then we use it to cluster the data points into groups or batches. Here we will focus on the Density-based spatial clustering of applications with noise (DBSCAN) clustering method.
