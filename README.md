images/final_customer_segments.png
# Retail Customer Segmentation Analysis

## Customer Intelligence Through Unsupervised Machine Learning

End-to-end customer segmentation project using transactional retail data and unsupervised learning techniques to identify meaningful customer groups and generate actionable business insights.

---

# Project Overview

Understanding customer behavior is essential for improving retention strategies, personalization, and business decision-making.

This project applies unsupervised machine learning techniques to segment customers based on purchasing behavior using the Online Retail II dataset.

The objective was to identify distinct customer profiles and translate clustering results into actionable business recommendations.

---

# Business Objective

The main objective of this analysis is to identify customer segments based on purchasing patterns, customer value, and engagement level.

The final segmentation framework aims to support:

- Customer retention strategies
- Personalized marketing campaigns
- Identification of high-value customers
- Customer reactivation opportunities

---

# Dataset

Dataset:
Online Retail II Dataset (UCI Machine Learning Repository)

The dataset contains transactional information from a UK-based online retailer between 2009 and 2011.

Main variables include:

- Invoice
- Customer ID
- Quantity
- Price
- Invoice Date
- Country

After data cleaning and preparation:

- 5,878 customers analyzed
- 1,067,371 transactions processed

---

# Methodology

The project followed a complete data science workflow:

## 1. Data Understanding

Exploration of:

- Dataset structure
- Missing values
- Data quality
- Initial distributions

## 2. Feature Engineering

Customer-level behavioral features were created:

- Recency
- Frequency
- Monetary Value
- Average Order Value
- Basket Size
- Customer Lifetime

## 3. Data Transformation

Applied:

- Log transformations
- Standardization
- PCA dimensionality reduction

to improve clustering performance.

---

# Unsupervised Learning Models

Three clustering algorithms were evaluated:

- K-Means
- Agglomerative Clustering
- Gaussian Mixture Model

Models were compared using:

- Silhouette Score
- Calinski-Harabasz Index
- Davies-Bouldin Index

---

# Model Selection

K-Means was selected as the final model due to:

- Best overall clustering performance
- Strong cluster separation
- High business interpretability

Final number of clusters:

**4 Customer Segments**

---

# Customer Segments

## Cluster 0 — VIP Loyal Customers

High-value customers with:

- Frequent purchases
- Recent activity
- Strong revenue contribution

Recommended strategy:
Retention and loyalty programs.

---

## Cluster 1 — One-Time / Churned Customers

Customers with:

- Low activity
- Long inactivity periods
- High churn risk

Recommended strategy:
Reactivation campaigns.

---

## Cluster 2 — High-Value Bulk Buyers

Customers characterized by:

- Large order values
- Large basket sizes

Recommended strategy:
Dedicated offers and volume-based incentives.

---

## Cluster 3 — Regular Customers

Stable customers with:

- Consistent purchasing behavior
- Growth potential

Recommended strategy:
Upselling and cross-selling initiatives.

---

# Project Results

The final model successfully identified meaningful customer groups and transformed transactional data into actionable business insights.

Key outcomes:

- Customer segmentation framework created
- Business-oriented customer profiles identified
- Recommendations developed for each segment

---

# Repository Structure
├── data
├── images
├── models
├── notebooks
└── README.md

---

# Technologies Used

Python

Libraries:

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# Author

Geronimo Fernandez

Data Science / Data Analytics Portfolio Project
