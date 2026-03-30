# 📊 Machine Learning  - Clustering Analysis

## 📌 Overview
This project applies **unsupervised machine learning (clustering)** techniques to two datasets:
- Loans Dataset
- Vehicle Dataset

The goal is to evaluate different clustering algorithms and determine the best approach using appropriate evaluation metrics.

---

## 📂 Datasets Used
- **Loans Dataset** – Contains applicant financial and demographic information  
- **Vehicle Dataset** – Contains geometric and shape-related features of vehicles  

---

## ⚙️ Methods Applied

### 🔹 Loans Dataset
Clustering was performed using:
- **K-Means**
- **Hierarchical Clustering**
- **DBSCAN**

Evaluation Metric:
- **Silhouette Score**

✅ **Result:**  
**DBSCAN** achieved the highest Silhouette Score and is the **best-performing algorithm** for the loans dataset.

---

### 🔹 Vehicle Dataset

Steps performed:
- Data preprocessing (scaling)
- **Elbow Method** (to estimate K)
- **Silhouette Score** (to validate K)

Clustering Algorithm:
- **K-Means**

✅ **Result:**  
- Optimal clusters: **K = 2**  
- Final clustering performed using **K-Means (K = 2)**  

---

## 📈 Key Insights

- **DBSCAN** is effective for datasets with noise and irregular cluster shapes.
- **K-Means** performs well when the number of clusters is clearly defined.
- **Silhouette Score** provides a more reliable evaluation compared to the Elbow Method.

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## 📌 Conclusion
Different datasets require different clustering approaches.  
- **DBSCAN** was best for the loans dataset  
- **K-Means (K = 2)** was optimal for the vehicle dataset  

The **Silhouette Score** proved to be the most effective method for evaluating clustering performance.

---

## 👤 Author
**Shilaku Innocent Omuyonga**  
- GitHub: [Shilaku-f1](https://github.com/Shilaku-f1)

---
