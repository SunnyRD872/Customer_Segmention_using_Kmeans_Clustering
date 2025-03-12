
# Customer Segmentation using K-Means Clustering

Overview

This project applies K-Means Clustering to segment customers based on their Annual Income and Spending Score. Customer segmentation helps businesses identify distinct customer groups and customize marketing strategies accordingly.


## Datasets

The dataset contains information about 200 customers, including their unique CustomerID, Gender, Age, Annual Income (in thousands of dollars), and Spending Score (ranging from 1 to 100). The Spending Score is assigned based on customer spending behavior. The data has been standardized to ensure consistency for analysis.


## Methodology

1.Data Preprocessing

-Extracted relevant features (Annual Income & Spending Score)

-Converted the data into a NumPy array

2.Finding Optimal Clusters (Elbow Method)

-Computed Within-Cluster Sum of Squares (WCSS) for different cluster numbers

-Plotted the Elbow Graph to determine the best k value

3.K-Means Clustering

-Applied K-Means algorithm with the optimal k=5

-Assigned each customer to a cluster

4.Visualization

-Used Matplotlib & Seaborn to visualize customer groups in a 2D space

-Plotted different clusters with their centroids
## Installation & Requirements

-numpy

-pandas

-matplotlib

-seaborn

-scikit-learn

## Results

This scatter plot represents customer segmentation based on Annual Income (x-axis) and Spending Score (y-axis). Different colors indicate distinct customer groups:

🔵 Blue: High spending, low income customers.

🔴 Red: High spending, high income customers.

🟢 Green: Low spending, low income customers.

⚫ Black: Low spending, high income customers.

🟡 Yellow: Moderate spending, moderate income
customers.

🔵 Cyan (large points): Cluster centroids representing the central points of each group.

This segmentation helps in identifying key customer behaviors for targeted marketing strategies.








##  Future Enhancements

-Experiment with other clustering algorithms (DBSCAN, Hierarchical Clustering)

-Include additional features (Age, Gender) for better segmentation
