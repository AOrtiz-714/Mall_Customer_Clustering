# Mall_Customer_Clustering
Mall-Customers-EDA-KMeans

Exploratory Data Analysiss and KMeans Clustering of Mall Customers

Mall Customers — EDA & Clustering

Project Overview

This project explores the Mall Customers dataset through Exploratory Data Analysis (EDA) and applies K-Means clustering to segment customers based on their spending behavior. The goal is to uncover actionable insights into customer groups and demonstrate practical skills in Python, data visualization, and unsupervised learning.

Objectives

Perform EDA using matplotlib and seaborn:
Analyze demographic and financial variables
Visualize relationships between income, spending, and age
Detect potential groupings from the data visually *Build a K-Means clustering model:
Select optimal number of clusters using Elbow & Silhouette methods
Assign customers to clusters
Interpret clusters into business-friendly customer segments
Dataset

Mall_Customers.csv
CustomerID: Unique identifier
Gender: Male/Female
Age: Customer age
Annual Income (k$): Annual income in thousands of dollars
Spending Score (1–100): Assigned score based on customer behavior & spending patterns
Tools & Libraries

Python 3.10+
Pandas — data handling
Matplotlib & Seaborn — EDA & visualization
Scikit-learn — clustering (K-Means, preprocessing, silhouette score)
NumPy — numerical computations
Exploratory Data Analysis

Univariate Analysis:
Age, Income, and Spending Score distributions
Gender balance
Bivariate Analysis:
Income vs Spending Score → distinct clusters visible
Spending Score by Gender
Age vs Spending Score
Correlation Heatmap:
Weak linear correlations overall
Reinforces need for clustering (non-linear separation)
Machine Learning Model: K-Means Clustering

Feature Selection:
Baseline: Annual Income & Spending Score
Extended: Age, Income, and Spending Score
Model Selection:
Evaluated k = 2–10 using Elbow and Silhouette Score
Chosen k based on peak silhouette (often k=5 for this dataset)
Results:
Segments identified (example labels):
Cluster 0: Low income, low spend → At-Risk
Cluster 1: High income, low spend → Potential Upsell
Cluster 2: Mid income, mid spend → Core Customers
Cluster 3: Low income, high spend → Value Shoppers
Cluster 4: High income, high spend → VIP / Premium
Business Value:
Marketing teams can target Potential Upsell customers with promotions
Loyalty programs can retain VIPs
Budget products can be directed toward Value Shoppers
Visualizations

Age, Income, and Spending distributions
Gender breakdown
Scatterplots (Income vs Spending, Age vs Spending)
Correlation heatmap
K-Means clusters with centroids
