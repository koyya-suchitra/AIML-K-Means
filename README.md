# K-Means Clustering on Mall Customers Dataset

This project demonstrates the application of the **K-Means clustering** algorithm on a customer dataset to segment customers into distinct groups based on their characteristics.

---

## 📚 Overview

K-Means is an **unsupervised machine learning algorithm** used to group similar data points into clusters. In this project, we cluster customers based on features such as age, annual income, and spending score, to discover meaningful customer segments.

---

## 🔍 Objectives

- Understand how K-Means clustering works.
- Use the **Elbow Method** to determine the optimal number of clusters (`K`).
- Apply K-Means clustering with the chosen `K`.
- Visualize the clusters using PCA for 2D representation.
- Evaluate clustering quality using the **Silhouette Score**.

---

## 🛠️ Tools & Libraries Used

- Python 3.x
- Pandas
- NumPy
- Matplotlib & Seaborn (for visualization)
- Scikit-learn (for K-Means, PCA, and Silhouette Score)

---

## 🚀 Steps Performed

1. **Data Loading and Preprocessing:**
   - Loaded the Mall Customers dataset.
   - Dropped irrelevant columns (e.g., CustomerID).
   - Encoded categorical variables (e.g., Gender).
   - Selected numeric features for clustering.

2. **Elbow Method to Find Optimal K:**
   - Calculated inertia for cluster counts from 1 to 10.
   - Plotted inertia vs number of clusters.
   - Identified the elbow point at **K = 5**.

3. **K-Means Clustering:**
   - Applied K-Means with `n_clusters=5`.
   - Assigned cluster labels to each customer.

4. **Cluster Visualization:**
   - Used PCA to reduce data to 2D.
   - Visualized clusters with different colors.

5. **Evaluation:**
   - Calculated Silhouette Score to assess cluster quality.

---

## 📈 Results

- Optimal clusters found at **K=5**.
- Silhouette Score indicates good separation and cohesion of clusters.
- Visualization shows clear cluster separation in 2D PCA space.

---

## 📝 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/kmeans-mall-customers.git
