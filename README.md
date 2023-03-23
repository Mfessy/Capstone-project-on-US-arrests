# Capstone-project-on-US-arrests
Clustering Analysis on US arrests Data set
Project Title: Clustering Analysis on US Arrests Dataset
Project Purpose: To perform clustering analysis on the US Arrests dataset using KMeans and hierarchical clustering and visualize the results using PCA.
Dataset: US Arrests dataset from a CSV file, which contains crime statistics from 50 states in the US.
Required Libraries: Pandas, NumPy, Matplotlib, StandardScaler, PCA, KMeans, and silhouette_score.
Steps Involved:
Load the dataset using Pandas and inspect its properties.
Preprocess the dataset by standardizing the features using StandardScaler.
Perform principal component analysis (PCA) on the standardized data to reduce its dimensionality to two.
Plot the first two principal components to visualize the data distribution.
Perform KMeans clustering with two clusters on the standardized data and calculate the silhouette score to evaluate the clustering quality.
Visualize the KMeans clustering results by coloring the points in the PCA plot based on their assigned labels.
Perform hierarchical clustering using the Ward linkage method on the standardized data and visualize the dendrogram to determine the optimal number of clusters.
Results: The KMeans clustering analysis showed that the US states can be divided into two distinct groups based on their crime statistics. The hierarchical clustering analysis using the dendrogram also suggested that two clusters would be appropriate for this dataset.
Future Work: This project can be extended by exploring other clustering algorithms and techniques, testing the performance of the models on different datasets, and tuning the hyperparameters to improve the clustering quality.
Author: [Mfesane Kunju]
