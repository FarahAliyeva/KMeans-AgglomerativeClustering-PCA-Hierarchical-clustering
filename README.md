# KMeans-AgglomerativeClustering-PCA-Hierarchical-clustering
Iris dataset clustering (K-Means, Hierarchical)  with PCA dimensionality reduction in Python.


# Iris Flower Clustering & Classification

This project applies both unsupervised learning (Clustering)  to the well-known **Iris Dataset**. 

The main objective of this project is to analyze, cluster, and predict different Iris flower species (Setosa, Versicolor, and Virginica) based on their morphological features.

---

##  Built With & Libraries

The project was developed using **Python** within a **Jupyter Notebook** environment. The core libraries used include:

* **Data Analysis:** `pandas`, `numpy`
* **Data Visualization:** `matplotlib`, `seaborn`
* **Machine Learning:**
  * `scikit-learn` (KMeans, AgglomerativeClustering, PCA, StandardScaler, LabelEncoder)
  * `scipy` (For Dendrogram and Linkage analysis)

---

##  Methods & Models Applied

The following steps and machine learning algorithms were implemented throughout the project:

1. **Data Preprocessing:** * Removing unnecessary features (`Id` column) and inspecting data structure using `info()` and `describe()`.
   * Feature scaling using `StandardScaler` to ensure all features are on the same scale.
2. **Clustering:**
   * **K-Means Clustering:** Optimal cluster size determination backed by Silhouette scores (`silhouette_score`).
   * **Hierarchical Clustering:** Building tree-like structures visualized via `dendrogram` and computed using `AgglomerativeClustering`.
3. **Dimensionality Reduction:**
   * **PCA (Principal Component Analysis)** was applied to reduce high-dimensional data, making visualization and modeling more effective.
