# 📘 Experiment 8: Effect of PCA on Regression and Classification Models

**(Dimensionality Reduction and Model Performance Analysis)**

---

## 📌 Objective

The objective of this experiment is to:

- Study the impact of **Principal Component Analysis (PCA)**
- Train models **with and without PCA**
- Compare performance using **5-Fold Cross-Validation**
- Analyze how PCA affects different types of models

---

## 🛠️ Tools & Libraries Used

- **NumPy**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn** –
  - PCA
  - Linear Regression
  - Random Forest Regressor
  - Logistic Regression
  - Support Vector Machine (SVM)
  - StandardScaler
  - Cross-validation tools

- **Jupyter Notebook**

---

## 📁 Repository Structure

```text
├── README.md
├── requirements.txt
├── Experiment_8.ipynb
├── Lab_Report_Exp8.pdf
├── datasets/
│   └── pca_dataset.csv
├── screenshots/
│   ├── scree_plot.png
│   ├── regression_results.png
│   ├── classification_results.png
│   └── comparison_plot.png
```

---

## 📂 Description of Files and Folders

### 🔹 `Experiment_8.ipynb`

Includes:

- Data preprocessing (handling missing values, scaling)
- PCA implementation
- Scree plot and explained variance analysis
- Regression models (Linear, Random Forest)
- Classification models (Logistic, SVM)
- 5-Fold CV comparison (with vs without PCA)

### 🔹 `datasets/`

- Dataset with ~1000 samples
- Mixed features
- Regression target: Final Score
- Classification target: Performance Level

### 🔹 `screenshots/`

- Scree plot
- Model performance comparison
- Cross-validation tables

---

## ▶️ How to Run

```bash
jupyter notebook
```

Run `Experiment_8.ipynb`.

---

## 📊 Output

- MSE and R² (Regression)
- Accuracy and F1-score (Classification)
- Scree plot
- Explained variance
- PCA vs Non-PCA comparison

---

## 📈 Models Implemented

### 🔹 Regression

- Linear Regression
- Random Forest Regressor

### 🔹 Classification

- Logistic Regression
- Support Vector Machine (SVM)

---

## 🎯 Learning Outcomes

- Understood **dimensionality reduction using PCA**
- Learned importance of **feature scaling before PCA**
- Observed that:
  - PCA helps **linear models more**
  - Tree-based models are less affected

- Reduced multicollinearity and noise

---

## 👤 Author

**Name:** Priya Verma
**Course:** Machine Learning Algorithms Laboratory (Semester VI)
**Experiment:** 8 – PCA Analysis
