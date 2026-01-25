# Experiment 4: Binary Classification using Linear and Kernel-Based Models

**(Logistic Regression and Support Vector Machine – SVM)**

---

## 📌 Objective

The objective of this experiment is to classify emails as **spam or ham** using **Logistic Regression** and **Support Vector Machine (SVM)** classifiers. The experiment focuses on analyzing the effect of **regularization, kernel selection, and hyperparameter tuning** on classification performance using standard evaluation metrics.

---

## 🛠️ Tools & Libraries Used

The following Python libraries are used in this experiment:

- **NumPy** – Numerical computations
- **Pandas** – Dataset loading and preprocessing
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualizations
- **Scikit-learn** –
  - Logistic Regression
  - Support Vector Machines (SVM)
  - Feature scaling
  - Hyperparameter tuning (GridSearchCV / RandomizedSearchCV)
  - Model evaluation metrics

- **Jupyter Notebook** – Interactive execution and documentation

---

## 📁 Repository Structure

```text
├── README.md
├── requirements.txt
├── Experiment_4.ipynb
├── datasets/
│   └── spambase.csv
├── screenshots/
│   ├── class_distribution.png
│   ├── confusion_matrix_logistic.png
│   ├── confusion_matrix_svm.png
│   ├── roc_curve_logistic.png
│   ├── roc_curve_svm.png
│   ├── svm_kernel_comparison.png
│   └── kfold_results.png
```

---

## 📂 Description of Files and Folders

### 🔹 `README.md`

Provides an overview of the experiment, tools used, repository structure, execution steps, and learning outcomes.

### 🔹 `Experiment_4.ipynb`

Jupyter Notebook containing the complete implementation, including:

- Dataset loading and preprocessing
- Exploratory Data Analysis (EDA)
- Baseline Logistic Regression
- Logistic Regression with L1 and L2 regularization
- SVM models with different kernels:
  - Linear
  - Polynomial
  - RBF
  - Sigmoid

- Hyperparameter tuning using Grid Search / Randomized Search
- 5-Fold Cross-Validation
- Performance evaluation and comparison

### 🔹 `datasets/`

Contains the dataset used in this experiment:

- **Spambase Dataset** (binary classification: spam / ham)

### 🔹 `screenshots/`

Contains screenshots of output visualizations generated during execution, including:

- Class distribution plots
- Confusion matrices
- ROC curves
- SVM kernel-wise performance comparison
- K-Fold cross-validation results

### 🔹 `requirements.txt`

Lists all required Python packages to ensure reproducibility.

---

## ▶️ How to Run the Experiment

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/<your-username>/<repository-name>.git
cd <repository-name>
```

### 2️⃣ Install Required Packages

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Jupyter Notebook

```bash
jupyter notebook
```

Open `Experiment_4.ipynb` and run all cells sequentially.

---

## 📊 Output

The experiment generates:

- Classification performance metrics:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - Training Time

- Confusion matrices for Logistic Regression and SVM
- ROC curves for both models
- Kernel-wise performance comparison for SVM
- 5-Fold cross-validation accuracy results
- Comparative analysis between Logistic Regression and SVM

All output visualizations are saved in the `screenshots/` folder.

---

## 📈 Models Implemented

- **Logistic Regression**
  - Baseline model
  - L1 (Lasso) regularization
  - L2 (Ridge) regularization

- **Support Vector Machine (SVM)**
  - Linear Kernel
  - Polynomial Kernel
  - RBF Kernel
  - Sigmoid Kernel

Hyperparameter tuning is performed using **Grid Search or Randomized Search with 5-Fold Cross-Validation**.

---

## 🎯 Learning Outcomes

- Implemented probabilistic and margin-based classifiers
- Understood the role of regularization in Logistic Regression
- Analyzed the effect of kernel selection in SVM
- Applied hyperparameter tuning techniques
- Evaluated classification models using standard metrics
- Interpreted bias–variance trade-offs in linear and kernel-based models

---

## 👤 Author

**Name:** Priya Verma
**Course:** Machine Learning Algorithms Laboratory (Semester VI)
**Experiment:** 4 – Binary Classification using Logistic Regression and SVM
