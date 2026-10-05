# Customer Segmentation using K-Means Clustering

## Overview

This project uses **K-Means Clustering**, an unsupervised machine learning algorithm, to segment customers into different groups based on their **annual income** and **spending score**.

The goal is to identify customers with similar spending behavior so that businesses can better understand their customer base and create more targeted marketing strategies.

## Dataset

The project uses the **Mall Customers dataset**, which contains information about mall customers, including:

- Customer ID
- Gender
- Age
- Annual Income
- Spending Score

For clustering, the model uses **Annual Income** and **Spending Score**.

## Model Used

### K-Means Clustering

K-Means is an **unsupervised learning algorithm** that divides data into a predefined number of groups called **clusters**.

The algorithm groups customers based on the distance between their feature values and the cluster centers. The cluster centers are repeatedly updated until the groups become stable.

In this project, the model creates **5 customer clusters**.

## Choosing the Number of Clusters

The **Elbow Method** is used to determine a suitable number of clusters.

It compares the **Within-Cluster Sum of Squares (WCSS)** for different numbers of clusters. The point where adding more clusters provides significantly less improvement is considered the elbow point.

Based on the analysis, **5 clusters** are selected for the final K-Means model.

## Results

The model divides customers into five groups based on their annual income and spending score.

The clusters are visualized using a scatter plot along with the **cluster centroids**, making it easier to understand the different customer segments and their spending patterns.

## Key Learning

This project demonstrates practical understanding of:

- Unsupervised Machine Learning
- K-Means Clustering
- Elbow Method
- Customer Segmentation
- Cluster Visualization
- Customer Spending Patterns

## Conclusion

K-Means clustering can be used to identify meaningful customer segments without predefined labels. In this project, customers are grouped according to their income and spending behavior, providing a simple approach to customer segmentation and exploratory business analysis.

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn


