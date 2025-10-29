# Mall Customer Segmentation using K-Means Clustering

![K-Means Cluster Plot](httpsd://raw.githubusercontent.com/YOUR_USERNAME/YOUR_REPO_NAME/main/cluster_plot.png)

## 📋 Project Overview
This project uses unsupervised machine learning to identify and profile distinct customer segments from a mall's dataset. By applying K-Means clustering, we can provide actionable insights for targeted marketing campaigns.

---

## 🚀 Technologies & Libraries
* **Python**
* **Pandas**: For data loading and manipulation.
* **Scikit-learn**: For K-Means clustering and `StandardScaler`.
* **Matplotlib / Seaborn**: For data visualization (Elbow Method plot, cluster plot).
* **Jupyter Notebook** (or VS Code)

---

## 🛠️ Project Workflow

1.  **Data Loading & Exploration:** Loaded the `Mall_Customers.csv` dataset.
2.  **Feature Selection:** Selected the `Annual Income (k$)` and `Spending Score (1-100)` features for clustering.
3.  **Data Preprocessing:** Applied `StandardScaler` to normalize the data, as K-Means is a distance-based algorithm.
4.  **Optimal 'k' Selection:** Implemented the **Elbow Method** to determine the optimal number of clusters (k=5) by analyzing WCSS (Within-Cluster Sum of Squares).
5.  **Model Training:** Trained the K-Means algorithm with `n_clusters=5`.
6.  **Cluster Visualization:** Created a scatter plot with **Matplotlib/Seaborn** to visualize the 5 distinct customer segments.

---

## 📈 Results & Interpretation

The analysis revealed 5 distinct customer segments:

* **Cluster 0 (Prime):** High Income, High Spending
* **Cluster 1 (Standard):** Average Income, Average Spending
* **Cluster 2 (Savers):** High Income, Low Spending
* **Cluster 3 (Sensible):** Low Income, Low Spending
* **Cluster 4 (Careless):** Low Income, High Spending

This segmentation allows the marketing team to design targeted strategies, such as loyalty programs for "Prime" customers and up-selling opportunities for "Savers."
