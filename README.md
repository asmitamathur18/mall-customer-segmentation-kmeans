Mall Customer Segmentation using K-Means Clustering

Project Overview
This project applies Unsupervised Machine Learning using the K-Means Clustering algorithm to segment mall customers based on their purchasing behavior.
The objective is to identify distinct customer groups using demographic and spending-related features to better understand purchasing patterns.

Two implementations are included:
Clustering using selected features (Annual Income and Spending Score)
Clustering using all features with label encoding and feature scaling

Dataset
The dataset used is Mall_Customers.csv, which contains:
Customer ID
Gender
Age
Annual Income (k$)
Spending Score (1–100)

Implementation 1: Two-Feature Clustering
Features Used
Annual Income
Spending Score

Steps Performed
Feature selection
Elbow Method to determine optimal clusters
K-Means clustering
2D cluster visualization

This version provides clear visual separation of customer segments.

Implementation 2: Full-Feature Clustering
Features Used
Gender (Label Encoded)
Age
Annual Income
Spending Score
Additional Steps
Label Encoding applied to Gender
Feature Scaling using StandardScaler
Elbow Method applied on scaled data

K-Means clustering performed in 4-dimensional feature space
Since clustering is performed in multi-dimensional space, direct 2D visualization is not fully representative of cluster boundaries.

Algorithm Used
K-Means Clustering
K-Means is an unsupervised learning algorithm that partitions data into K distinct clusters based on distance from cluster centroids.

Elbow Method
The Elbow Method is used to determine the optimal number of clusters by analyzing the Within-Cluster Sum of Squares (WCSS).

Technologies Used
Python
NumPy
Pandas
Matplotlib
Scikit-learn

Repository Structure
mall-customer-segmentation-kmeans/
│
├── Mall_Customers.csv
├── KMeans_Clustering.ipynb
├── KMeans_FullFeature_Clustering.ipynb
└── README.md

Learning Outcomes
Understanding of Unsupervised Learning
Implementation of K-Means clustering


Use of the Elbow Method
Label Encoding for categorical features
Feature Scaling using StandardScaler
Multi-dimensional clustering analysis

Future Improvements
Add Silhouette Score evaluation
Compare with Hierarchical Clustering

Perform PCA for dimensionality reduction and visualization

Deploy as a small interactive web application
