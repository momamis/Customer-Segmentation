# Customer Segmentation
Customer Segmentation of Mall Customers Using KMeans Clustering
![Scatter Plot](https://github.com/momamis/Customer-Segmentation/blob/main/clustering_bivaariate.png)

## Executive Summary
This project applies KMeans clustering to segment customers based on their demographics and spending behavior from the Mall Customers dataset. By exploring the dataset using univariate, bivariate, and multivariate clustering approaches, we gain insights into customer profiles that can inform business strategies like personalized marketing and customer retention.

## Steps Taken
- Exploratory data analysis (EDA) with KDE plots and box plots visualizing Age, Income, and Spending Score across genders.
- Univariate Clustering using `Annual Income (k$)`.
- Bivariate Clustering using `Annual Income (k$)` and `Spending Score (1-100)` with 5 clusters chosen via the Elbow Method to obtain cluster means and gender proportions per cluster.
- Encoding `gender` with `get_dummies` and scaling features with `Standard Scaler` for multivariate clustering.

## Insights 
- Cluster 2 individuals could be the target group, representing young, mostly female customers with high spending scores. They are ideal targets for upselling and premium product promotions.
- Cluster 1 accounts for middle-aged customers with average income and spending. They represent a stable segment that could be loyal with personalized engagement.
- Cluster 4 highlights an interesting opportunity to market to customers sales events for popular items.
