# 🛍️ Clustering Analysis: Online Retail Case Study

## 📖 Overview

This project focuses on **customer segmentation** using unsupervised learning techniques like **K-Means** and **Gaussian Mixture Models** on an **Online Retail dataset**. The goal is to identify distinct customer groups based on purchasing behavior to enable better marketing and business strategies.

---

## 🧰 Technologies Used

- Python 3.x  
- **Pandas**, **NumPy** – Data handling and preprocessing  
- **Matplotlib**, **Seaborn**, **Plotly** – Data visualization  
- **Scikit-learn** – Clustering algorithms and evaluation metrics  
- **Yellowbrick** – Visualizing optimal clusters  
- **Missingno** – Visualizing missing data

---


## ⚙️ Workflow

### 1. Data Preprocessing

- Removed null or invalid entries  
- Feature extraction (Recency, Frequency, Monetary - RFM)  
- Feature scaling using `MinMaxScaler`

### 2. Exploratory Data Analysis (EDA)

- Histograms, scatter plots, heatmaps  
- Missing value visualization using `missingno`

### 3. Clustering Techniques

- **K-Means Clustering**  
- **Gaussian Mixture Models (GMM)**  
- (Optional comparison with DBSCAN and Agglomerative Clustering)

### 4. Cluster Evaluation Metrics

- **Silhouette Score** – Measures how similar a data point is to its own cluster vs. other clusters  
- **Davies-Bouldin Index** – Measures average similarity ratio between clusters  
- **Calinski-Harabasz Score** – Measures ratio of between-cluster dispersion to within-cluster dispersion

### 5. Visualization

- 2D/3D cluster plots  
- Pair plots and heatmaps for cluster profiling

---

## 📌 Conclusion

This clustering approach helps businesses:

- Understand customer behavior  
- Personalize marketing strategies  
- Improve customer retention and satisfaction

---

## 📎 References

- UCI Machine Learning Repository – Online Retail Dataset  
- Scikit-learn Documentation  
- Plotly Visualizations
