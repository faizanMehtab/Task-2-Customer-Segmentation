Customer Segmentation Using K-Means Clustering

Data Science & Analytics Internship – DevelopersHub Corporation

## Project Overview

Customer segmentation is a crucial marketing strategy that helps businesses understand customer behavior and target them effectively.
This project applies unsupervised machine learning (K-Means clustering) to segment mall customers based on their income and spending patterns.

### Objective

Segment customers into meaningful groups

Analyze customer spending behavior

Propose targeted marketing strategies for each segment

# Dataset

Mall Customers Dataset

Source: Kaggle

Contains customer demographic and spending information

Key Features Used

Annual Income (k$)

Spending Score (1–100)

## Tools & Technologies

Python

Jupyter Notebook

pandas, numpy

matplotlib, seaborn

scikit-learn

# Methodology

## Data Loading & Exploration

Loaded dataset and inspected structure

Performed basic exploratory data analysis (EDA)

Visualized income and spending patterns

## Feature Selection & Scaling

Selected income and spending score for clustering

Applied StandardScaler to normalize features

## Optimal Cluster Selection

Used the Elbow Method to determine optimal number of clusters

Identified K = 5 as the ideal number of customer segments

## K-Means Clustering

Applied K-Means algorithm

Assigned cluster labels to customers

## Visualization

Visualized clusters using scatter plots

Used PCA for dimensionality reduction and improved visualization

## Cluster Insights & Marketing Strategies

Cluster 0: High Income – High Spending
Strategy: Premium offers, loyalty programs

Cluster 1: Low Income – Low Spending
Strategy: Discounts, budget-friendly products

Cluster 2: High Income – Low Spending
Strategy: Personalized promotions to boost engagement

Cluster 3: Low Income – High Spending
Strategy: Value bundles, installment offers

Cluster 4: Average Income – Average Spending
Strategy: Standard marketing campaigns

# Conclusion

K-Means clustering successfully segmented customers into five distinct groups.
These insights can help businesses design targeted marketing strategies and improve customer satisfaction.
