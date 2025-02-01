# Gene-Expression-Data-Clustering-and-Analysis

# Overview

This project involves clustering gene expression data using dimensionality reduction techniques (PCA) followed by clustering algorithms (K-means). The dataset comprises 40 samples with measurements for 1,000 genes. The objective is to determine whether the data can be clustered into two distinct groups, representing healthy and diseased samples.

# Objective

1. Reduce the dimensionality of the gene expression data using Principal Component Analysis (PCA).

2. Perform clustering using K-means with K=2.

3. Evaluate the clustering performance using the Silhoutte score.

4. Visualizd the clustered data.

# Dataset Description

1. **Dataset** : Contains 40 tissue samples and 1,000 gene expression measurement.

2.  **Group Information** : The first 20 samples are from healthy patients, and the next 20 are from diseased patients.

# Methodology

<ins>1. Data Preprocessing</ins>

1. The dataset was loaded and split into features for analysis.

2. Standard scaling was applied to ensure features have a mean of 0 and a standard deviation of 1.

<ins>2. Dimensionality Reduction</ins>

1. **PCA** : Principal Component Analysis was applied to reduce the dimensionality of the dataset to the top 2 principal components.

<ins>3. Clustering</ins>

1. **K-Means** : The K-means clustering algorithm was used with K = 2 to cluster the data into two groups.

2. **Evaluation Metric** : The Silhoutte score was calculated to assess the quality of the clustering technique.

<ins>4. Visualization</ins>

The clustered data was visualized using scatter plots of the first two principal components.

# Results

1. **Silhoutte Score** : 0.6407 (Indicates moderate to good clustering).

2. **Visualization** : The scatter plot shows clear separation between the two clusters, though some overlap exists.

# Conclusion

1. PCA effectively reduced the dimensionality of the gene expression data while retaining variance.

2. K-means clustering demonstrated the ability to separate the samples into two distinct clusters, corresponding to the healthy and diseased groups.

3. The Silhoutte score of 0.6407 suggests that the clustering solution is well defined.

# Requirements

1. pandas

2. numpy

3. scikit-learn

4. matplotlib
