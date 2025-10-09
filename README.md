# Customer Segmentation Using Clustering Algorithms

## Overview
This project performs customer segmentation on the Mall Customers dataset using clustering techniques. The goal is to group customers based on their annual income and spending score, which helps businesses tailor marketing strategies for different customer segments.

## Dataset
The dataset is the "Mall Customers" dataset, available on Kaggle. It contains customer information including:

- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

## Methodology
1. **Data Exploration & Visualization**  
   Visualized the relationship between Annual Income and Spending Score.

2. **Data Preprocessing**  
   Standardized the features to ensure equal weighting during clustering.

3. **K-Means Clustering**  
   - Used the Elbow Method to find the optimal number of clusters (k=5).  
   - Applied K-Means clustering and visualized the clusters.  
   - Calculated average income and spending score per cluster.

4. **DBSCAN Clustering (Bonus)**  
   - Applied DBSCAN algorithm to detect clusters without specifying cluster number.  
   - Visualized clusters including noise points.

## Tools & Libraries
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn

