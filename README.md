# 🧠 Customer Segmentation using Clustering Techniques

This project performs customer segmentation using **unsupervised machine learning techniques** like **K-Means Clustering** and **Hierarchical Clustering** to help a retail company better understand customer behavior and improve targeted marketing strategies.

## 📂 Files Included

- `Customers.csv` – Raw customer data including Age, Annual Income, and Spending Score.
- `kmeans_clustering.ipynb` – Implementation of K-Means clustering with visualization and elbow method.
- `Hierarchical Clustering.ipynb` – Hierarchical clustering with dendrogram and agglomerative results.
- `feature_selection_unsupervised_learning.ipynb` – Feature selection to remove redundant or low-variance features and evaluate clustering impact.

---

## 📊 Dataset Overview

The dataset contains the following attributes:

- **CustomerID**: Unique identifier
- **Gender**: Male/Female (not used in clustering)
- **Age**: Age of the customer
- **Annual Income (k$)**: Customer's yearly income in thousands
- **Spending Score (1–100)**: Score assigned by the company based on spending behavior

---

## 🔍 Objective

Group customers into segments based on:
- **Spending habits**
- **Income level**
- **Age-related trends**

This segmentation helps in designing personalized marketing strategies and promotions.

---

## 🔧 Techniques Used

### ✅ K-Means Clustering
- Standardized the data using `StandardScaler`
- Used **Elbow Method** to determine optimal number of clusters (k = 5)
- Visualized cluster patterns and centroids

### ✅ Hierarchical Clustering
- Built **dendrogram** using `scipy`'s `linkage` function
- Applied **Agglomerative Clustering**
- Visualized cluster distributions

### ✅ Feature Selection
- Removed **low-variance** features using `VarianceThreshold`
- Checked for **highly correlated features** to avoid redundancy
- Re-applied clustering for performance comparison

---

## 📈 Visual Results

- Cluster visualizations highlight key customer groups:
  - High-income, high-spending (ideal targets)
  - Low-income, low-spending (budget customers)
  - Young frequent shoppers with mid income
- Dendrogram showed natural grouping tendencies before assigning clusters

---

## 🧩 Key Learnings

- Clustering is useful when labels are not provided
- Preprocessing and feature selection can significantly impact clustering quality
- K-Means is fast and intuitive, while Hierarchical provides more interpretable structure

---
