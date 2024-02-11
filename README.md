# Clustering
Clustering using different techniques, parameters, preprocessing methods and cluster sizes.

## Parameters used:
1. Silhouette - The silhouette score is specialized for measuring cluster quality when the clusters are convex-shaped, and may not perform well if the data clusters have irregular shapes or are of varying sizes. The silhouette can be calculated with any distance metric, such as the Euclidean distance or the Manhattan distance. ![](https://www.google.com/url?sa=i&url=https%3A%2F%2Fstackoverflow.com%2Fquestions%2F31762165%2Fsklearn-silhouette-score-different-for-same-clustering&psig=AOvVaw2zSZ70V3SpJFN3iLSyB7Fg&ust=1707762094695000&source=images&cd=vfe&opi=89978449&ved=0CBMQjRxqFwoTCLD16dzzo4QDFQAAAAAdAAAAABAk)

2. Calinski Harabasz - Calinski–Harabasz index (CHI), also known as the Variance Ratio Criterion (VRC), is a metric for evaluating clustering algorithms. It is an internal evaluation metric, where the assessment of the clustering quality is based solely on the dataset and the clustering results, and not on external, ground-truth labels.
3. Davies Bouldins - The Davies-Bouldin Index is a validation metric that is used to evaluate clustering models. It is calculated as the average similarity measure of each cluster with the cluster most similar to it. In this context, similarity is defined as the ratio between inter-cluster and intra-cluster distances.
