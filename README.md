# 🛍️ Mall Customer Segmentation using K-Means Clustering

## 📌 Project Overview
This project performs **customer segmentation** using the **K-Means clustering algorithm** on the Mall Customers dataset.  
The goal is to group customers based on their **Annual Income, Spending Score, and Age** to identify different customer segments.

---

## 📂 Dataset Information
The dataset contains **200 customer records** with the following features:

- CustomerID  
- Gender  
- Age  
- Annual Income (k$)  
- Spending Score (1-100)  

---

## 🔧 Technologies Used
- Python 🐍  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 📊 Data Preprocessing
- Checked for missing values (none found ✅)
- Converted categorical data (**Gender**) using Label Encoding
- Selected important features:
  - Annual Income
  - Spending Score
  - Age

---

## 📈 Exploratory Data Analysis
- Correlation heatmap used to understand relationships between variables
- Visualized data distribution using plots

---

## 🤖 Model Used: K-Means Clustering
- Used **Elbow Method** to determine optimal number of clusters
- Chose **K = 4 clusters**
- Model trained using:
  ```python
  KMeans(n_clusters=4, random_state=42)




  Elbow Method
Calculated WCSS (Within Cluster Sum of Squares)
Plotted graph to find optimal K value



📊 Clustering Results
Customers grouped into 4 clusters
Each cluster represents different spending behavior:
High income – high spending
High income – low spending
Low income – high spending
Low income – low spending
