# 📘 Experiment 9: Clustering Human Activity Recognition Data

**(Unsupervised Learning and Cluster Analysis)**

---

## 📌 Objective

The objective of this experiment is to:

- Implement clustering algorithms:
  - **K-Means**
  - **DBSCAN**
  - **Hierarchical Clustering**

- Visualize clusters and compare performance
- Evaluate clustering using internal and external metrics

---

## 🛠️ Tools & Libraries Used

- **NumPy**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn** –
  - KMeans
  - DBSCAN
  - AgglomerativeClustering
  - PCA / t-SNE
  - Clustering metrics

- **SciPy** – Dendrogram visualization
- **Jupyter Notebook**

---

## 📁 Repository Structure

```text
├── README.md
├── requirements.txt
├── Experiment_9.ipynb
├── Lab_Report_Exp9.pdf
├── datasets/
│   └── HAR_dataset.csv
├── screenshots/
│   ├── elbow_curve.png
│   ├── silhouette_plot.png
│   ├── cluster_visualization.png
│   └── dendrogram.png
```

---

## 📂 Description of Files and Folders

### 🔹 `Experiment_9.ipynb`

Includes:

- Data preprocessing and normalization
- PCA/t-SNE for visualization
- K-Means clustering (Elbow method)
- DBSCAN clustering
- Hierarchical clustering with dendrogram
- Evaluation using clustering metrics

### 🔹 `datasets/`

- Human Activity Recognition Dataset
- 6 activity classes (walking, sitting, etc.)
- Sensor-based features

### 🔹 `screenshots/`

- Elbow curve (k vs WCSS)
- Silhouette score plot
- Cluster scatter plots
- Dendrogram

---

## ▶️ How to Run

```bash
jupyter notebook
```

Run `Experiment_9.ipynb`.

---

## 📊 Output

- Elbow curve
- Silhouette scores
- Cluster visualizations
- Dendrogram
- Evaluation metrics:
  - Silhouette Score
  - Davies–Bouldin Index
  - Adjusted Rand Index (ARI)
  - NMI

---

## 📈 Models Implemented

- **K-Means Clustering**
  - Optimal k using Elbow method

- **DBSCAN**
  - Density-based clustering
  - Noise detection

- **Hierarchical Clustering**
  - Agglomerative approach
  - Ward linkage

---

## 🎯 Learning Outcomes

- Understood **unsupervised learning techniques**
- Learned how to **select optimal clusters**
- Compared clustering algorithms
- Observed:
  - K-Means works well for spherical clusters
  - DBSCAN handles noise effectively
  - Hierarchical clustering provides cluster hierarchy

---

## 👤 Author

**Name:** Priya Verma
**Course:** Machine Learning Algorithms Laboratory (Semester VI)
**Experiment:** 9 – Clustering Analysis
