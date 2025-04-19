# Pima Indian Diabetes Dataset Analysis and Clustering

This repository contains the implementation for analyzing the Pima Indian Diabetes dataset. The project encompasses several key stages:

**1. Preprocessing:**
   - Data cleaning and handling of missing values (if any).
   - Feature scaling and normalization to prepare the data for analysis and clustering algorithms.

**2. Exploratory Data Analysis (EDA):**
   - Initial investigation of the dataset to understand its characteristics.
   - Visualization of data distributions, relationships between features, and potential patterns.

**3. Hierarchical Clustering:**
   - Implementation of a hierarchical clustering algorithm (e.g., AGNES - Agglomerative Nesting) to identify natural groupings within the data.
   - Evaluation of the clustering hierarchy and determination of an appropriate number of clusters.

**4. K-Means Clustering:**
   - Application of the K-Means partitioning algorithm to cluster the data based on the number of clusters identified (potentially informed by the hierarchical clustering results).
   - Evaluation of the resulting clusters.

**5. DBSCAN Clustering:
   - Application of the DBSCAN algorithm to identify density-based clusters and noise points, with parameter tuning for ϵ and MinPts.
   - Evaluation of clusters and comparison with K-Means to highlight DBSCAN’s ability to handle outliers and irregular shapes.

**Further details regarding the implementation, including code, output visualizations, and explanatory comments, can be found within the project files.**
