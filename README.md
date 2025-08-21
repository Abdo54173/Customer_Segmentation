Customer Segmentation using K-Means
Project Overview

This project performs customer segmentation on the Mall Customers dataset from Kaggle. By analyzing Annual Income and Spending Score, customers are grouped into meaningful segments using K-Means clustering. The results are visualized in 2D plots to help businesses understand customer spending patterns and target marketing strategies effectively.

Dataset

Source: Mall Customers Dataset on Kaggle

Features Used:

Annual Income (k$)

Spending Score (1-100)

Methodology

Data Loading & Exploration:

Inspect the dataset, check for missing values, and perform descriptive statistics.

Feature Selection:

Use Annual Income and Spending Score as clustering features.

Scaling:

Apply StandardScaler to normalize the features for fair distance calculation.

K-Means Clustering:

Determine optimal number of clusters using Elbow Method.

Apply K-Means to segment customers into distinct groups.

Visualization:

Scatter plots with different colors for each cluster and centroids marked.

How to Run

Clone the repository:

git clone https://github.com/Abdo54173/Customer_Segmentation.git


Install dependencies:

pip install pandas numpy matplotlib seaborn scikit-learn


Run the notebook or script:

jupyter notebook Customer_Segmentation.ipynb


Explore the visualizations and cluster assignments.

Results

Customers are grouped into clusters such as:

High Income, High Spending

High Income, Low Spending

Low Income, High Spending

Low Income, Low Spending

Average Customers

Scatter plots clearly show the separation of clusters based on scaled features.
