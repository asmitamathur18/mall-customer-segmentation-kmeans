Mall Customer Segmentation using K-Means Clustering
Project Overview:
This project applies Unsupervised Machine Learning using the K-Means Clustering algorithm to segment mall customers based on their purchasing behavior.

The goal is to identify distinct customer groups using features such as:
-> Annual Income
-> Spending Score

This helps in understanding customer patterns for better marketing strategies and targeted campaigns.

Algorithm Used:-
K-Means Clustering
K-Means is an unsupervised learning algorithm that groups data points into K distinct clusters based on similarity.

Elbow Method:-
The Elbow Method was used to determine the optimal number of clusters by analyzing the Within-Cluster Sum of Squares (WCSS).

Technologies Used:-
Python
NumPy
Pandas
Matplotlib
Scikit-learn

Project Workflow:-
Import dataset (Mall_Customers.csv)
Perform data preprocessing
Select relevant features (Income and Spending Score)
Apply Elbow Method to find optimal K
Train K-Means model
Visualize customer clusters

Output:-
Identified distinct customer segments
Visualized clusters using 2D scatter plots
Clearly separated high-spending, mid-range, and low-spending customer groups

Repository Structure:-
mall-customer-segmentation-kmeans/
│
├── Mall_Customers.csv
├── KMeans_Clustering.ipynb
└── README.md

Learning Outcomes:-
Understanding of Unsupervised Learning
Implementation of K-Means algorithm
Cluster visualization using Matplotlib
Determining optimal cluster count using Elbow Method

Future Improvements:-
Add 3D visualization
Try hierarchical clustering
Compare clustering performance metrics
