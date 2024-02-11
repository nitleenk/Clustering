# Clustering
Clustering using different techniques, parameters, preprocessing methods and cluster sizes.

## Parameters used:
1. Silhouette - The silhouette score is specialized for measuring cluster quality when the clusters are convex-shaped, and may not perform well if the data clusters have irregular shapes or are of varying sizes. The silhouette can be calculated with any distance metric, such as the Euclidean distance or the Manhattan distance. ![image](https://github.com/nitleenk/Clustering/assets/127779292/c21f8d59-e30f-431f-af77-7a88b6b1e4ea)


2. Calinski Harabasz - Calinski–Harabasz index (CHI), also known as the Variance Ratio Criterion (VRC), is a metric for evaluating clustering algorithms. It is an internal evaluation metric, where the assessment of the clustering quality is based solely on the dataset and the clustering results, and not on external, ground-truth labels.
3. Davies Bouldins - The Davies-Bouldin Index is a validation metric that is used to evaluate clustering models. It is calculated as the average similarity measure of each cluster with the cluster most similar to it. In this context, similarity is defined as the ratio between inter-cluster and intra-cluster distances.
