
# Clustering
A Comparative Performance Study of Various Clustering Algorithms Utilizing Different Pre-processing Techniques, Varied Numbers of Clusters, and Evaluation Metrics

# Clustering: An Overview
Clustering, an essential technique in unsupervised machine learning, groups similar data points based on specific features or characteristics. The primary aim is to uncover inherent patterns, structures, or relationships within the data without predefined labels. Clustering finds applications in diverse fields, such as data analysis, pattern recognition, image segmentation, and customer segmentation.

# Key Concepts:
# 1. Objective
The primary objective of clustering is to partition a dataset into groups or clusters, where points within the same cluster are more similar to each other than to those in other clusters.

# 2. Similarity Measure
Clustering relies on a similarity measure to quantify the likeness between data points. Common metrics include Euclidean distance, cosine similarity, and correlation coefficient.

# Clustering Methods:
# 1. K-Means Clustering
K-Means is a popular partitioning method that divides the dataset into 'k' clusters, minimizing the sum of squared distances between data points and their assigned cluster centroids. The algorithm iteratively refines cluster assignments until convergence.

# 2. Affinity Propagation
Affinity Propagation identifies exemplars (representative points) and assigns each point to the nearest exemplar based on similarity. It's suitable for diverse cluster shapes and sizes without requiring the predefined number of clusters 'k'.

# 3. Mean Shift Clustering
Mean Shift is a density-based method identifying cluster centers by iteratively shifting towards the mode of the data distribution. It can detect clusters with irregular shapes and sizes.

# 4. Spectral Clustering
Spectral Clustering leverages eigenvalues to reduce data dimensionality before clustering, effective for non-convex clusters and capturing complex relationships.

# 5. Agglomerative Clustering
Agglomerative Clustering is a hierarchical method that merges the most similar clusters until only one remains, illustrated by a dendrogram.

# 6. Density-Based Spatial Clustering (DBSCAN)
DBSCAN identifies clusters based on data point density, grouping closely packed points and separating outliers. It discovers clusters of arbitrary shapes without specifying the number of clusters.

# 7. OPTICS Clustering
Ordering Points To Identify the Clustering Structure (OPTICS) extends DBSCAN, allowing flexible cluster extraction for varying densities and shapes.

# 8. Birch Clustering
BIRCH (Balanced Iterative Reducing and Clustering using Hierarchies) is a hierarchical algorithm for large datasets, incrementally building a tree-like structure.
# Conclusions

1. In context of **no data preprocessing** among the 8 types of clustering provided , the **Kmeans clustering** gave the best silhouette value with **no of clusters = 3**

2. In context of using **normalization**, among the 8 types of clustering provided , the **Spectral Clustering** gave the best silhouette value with **no of clusters = 3**

3. In context of using **transformation**, among the 8 types of clustering provided , the **Kmeans clustering** gave the best silhouette value with **no of clusters = 3**

4. In context of using **PCA**, among the 8 types of clustering provided , the **Kmeans clustering** gave the best silhouette value with **no of clusters = 3**
 
5. In context of using **normalization + transformation**, among the 8 types of clustering provided , the **Spectral Clustering** gave the best silhouette value with **no of clusters = 3**

6. In context of using **normalization + transformation + PCA**, among the 8 types of clustering provided , the **Spectral Clustering** gave the best silhouette value with **no of clusters = 3**
