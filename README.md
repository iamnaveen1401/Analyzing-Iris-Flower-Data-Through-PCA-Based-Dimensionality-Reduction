# 🌺 Analyzing Iris Flower Data Through PCA-Based Dimensionality Reduction

## 📘 Project Overview
This project explores the **Iris flower dataset** using **Principal Component Analysis (PCA)** to perform dimensionality reduction.  
By transforming the original four-dimensional feature space into two or three components, the project aims to visualize relationships between Iris species and identify key features that drive data variance.

---

## 🧩 Dataset Information
- **Dataset Source:** `sklearn.datasets.load_iris`  
- **Samples:** 150  
- **Features:**  
  - Sepal Length  
  - Sepal Width  
  - Petal Length  
  - Petal Width  
- **Classes:**  
  - Iris-setosa  
  - Iris-versicolor  
  - Iris-virginica  

The Iris dataset is one of the most popular benchmark datasets in machine learning and is ideal for exploring dimensionality reduction and data visualization.

---

## 🎯 Objective
To apply **PCA** for transforming and visualizing the Iris dataset in a lower-dimensional space while retaining most of its variance.  
This helps to uncover **patterns**, **correlations**, and **class separability** across different flower species.

---

## ⚙️ Implementation Steps
1. Load the dataset from `sklearn.datasets.load_iris`  
2. Standardize features using `StandardScaler`  
3. Apply **PCA** to reduce data to 2D or 3D space  
4. Visualize principal components to understand clustering  
5. Analyze explained variance ratio of components  

---
