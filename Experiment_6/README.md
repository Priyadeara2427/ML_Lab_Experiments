# Experiment 6: Decision Tree and Random Forest — A Comparative Classification Study

**(Tree-Based Models and Ensemble Learning)**

---

## 📌 Objective

The objective of this experiment is to:

- Implement a **Decision Tree classifier**
- Extend it into a **Random Forest ensemble model**
- Study the impact of hyperparameters on overfitting and generalization
- Perform **5-Fold Cross-Validation** for model selection
- Compare single-tree and ensemble models

---

## 🛠️ Tools & Libraries Used

- **NumPy** – Numerical operations

- **Pandas** – Data handling

- **Matplotlib** – Visualization

- **Seaborn** – Feature correlation analysis

- **Scikit-learn** –
  - Decision Tree
  - Random Forest
  - GridSearchCV
  - Model evaluation metrics

- **Jupyter Notebook** – Implementation environment

---

## 📁 Repository Structure

```text
├── README.md
├── requirements.txt
├── Experiment_6.ipynb
├── Lab_Report_Exp6.pdf
├── datasets/
│   └── breast_cancer.csv
├── screenshots/
│   ├── class_distribution.png
│   ├── feature_correlation.png
│   ├── confusion_matrix.png
│   └── roc_curve.png
```

---

## 📂 Description of Files and Folders

### 🔹 `README.md`

Provides experiment overview and execution guide.

### 🔹 `Experiment_6.ipynb`

Contains implementation steps:

- Dataset loading and preprocessing
- Exploratory Data Analysis
- Decision Tree training
- Hyperparameter tuning using 5-Fold CV
- Random Forest implementation
- Performance comparison
- ROC curve and confusion matrix visualization

### 🔹 `datasets/`

Contains:

- Wisconsin Diagnostic Breast Cancer Dataset from
  UCI Machine Learning Repository
- 569 samples with 30 numerical features
- Binary classification (Malignant / Benign)

### 🔹 `screenshots/`

Contains:

- Class distribution
- Feature correlation heatmap
- Confusion matrices
- ROC curves

### 🔹 `requirements.txt`

Lists required dependencies.

---

## ▶️ How to Run the Experiment

### 1️⃣ Clone Repository

```bash
git clone https://github.com/<your-username>/<repository-name>.git
cd <repository-name>
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run Notebook

```bash
jupyter notebook
```

Open `Experiment_6.ipynb` and run all cells.

---

## 📊 Output

The experiment generates:

- Accuracy, Precision, Recall, F1-score
- Confusion matrices
- ROC curve and AUC score
- Cross-validation results
- Decision Tree vs Random Forest comparison
- Hyperparameter tuning results

---

## 📈 Models Implemented

- **Decision Tree**
  - Gini / Entropy splitting
  - Tree depth control
  - Hyperparameter tuning

- **Random Forest**
  - Bootstrap aggregation
  - Random feature selection
  - Ensemble prediction

---

## 🎯 Learning Outcomes

- Implemented tree-based classification models
- Understood overfitting in decision trees
- Learned ensemble learning concepts
- Applied cross-validation for model selection
- Compared single model vs ensemble performance
- Analyzed bias–variance tradeoff

---

## 👤 Author

**Name:** Priya Verma
**Course:** Machine Learning Algorithms Laboratory (Semester VI)
**Experiment:** 6 – Decision Tree and Random Forest

---
