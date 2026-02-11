 Customer Segmentation using K-Means Clustering

 Project Overview

This project focuses on customer segmentation using K-Means clustering on the Mall Customers dataset.
The goal is to group customers based on their purchasing behavior so that businesses can better understand customer patterns and design targeted marketing strategies.

📊 Dataset Overview

Dataset Name: Mall_Customers.csv

Type: Public dataset

Attributes:

Gender

Age

Annual Income (k$)

Spending Score (1–100)

The dataset is included in this repository for reproducibility.

🛠️ Tools & Libraries Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook

🔍 Exploratory Data Analysis (EDA)

The following analyses were performed:

Distribution of Gender, Age, Annual Income, and Spending Score

Correlation analysis using a heatmap

Gender-based analysis using box plots, violin plots, and swarm plots

These visualizations help in understanding customer behavior before clustering.

🤖 Clustering Methodology

Algorithm Used: K-Means Clustering

Cluster Selection: Elbow Method

Clustering Approaches:

2D clustering using Annual Income and Spending Score

3D clustering using Age, Annual Income, and Spending Score

📈 Visualization of Clusters

2D scatter plots for customer segmentation

3D scatter plots for better cluster interpretation

PCA (Principal Component Analysis) used for 2D visualization of clusters formed using three features

📌 Results & Insights

Customers are segmented into 5 distinct clusters

Each cluster represents a different customer group based on income and spending behavior

Cluster-wise mean analysis helps identify:

High-value customers

Low-spending customers

Potential target segments
