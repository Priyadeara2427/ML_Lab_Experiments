# 📘 Experiment 7: Bagging, Boosting, and Stacked Ensemble Models

**(Advanced Ensemble Learning Techniques)**

---

## 📌 Objective

The objective of this experiment is to:

- Understand **ensemble learning techniques**: Bagging, Boosting, and Stacking
- Implement **Bagging and Boosting classifiers**
- Build a **Stacked Ensemble model** using multiple base learners
- Perform **5-Fold Cross-Validation** for model selection
- Compare ensemble models based on performance and generalization

---

## 🛠️ Tools & Libraries Used

- **NumPy** – Numerical operations
- **Pandas** – Data handling
- **Matplotlib** – Visualization
- **Seaborn** – Data analysis and plots
- **Scikit-learn** –
  - BaggingClassifier
  - AdaBoostClassifier
  - GradientBoostingClassifier
  - StackingClassifier
  - GridSearchCV
  - Evaluation metrics

- **Jupyter Notebook** – Implementation environment

---

## 📁 Repository Structure

```text
├── README.md
├── requirements.txt
├── Experiment_7.ipynb
├── Lab_Report_Exp7.pdf
├── datasets/
│   └── breast_cancer.csv
├── screenshots/
│   ├── ensemble_comparison.png
│   ├── confusion_matrix.png
│   ├── roc_curve.png
│   └── cv_results.png
```

---

## 📂 Description of Files and Folders

### 🔹 `Experiment_7.ipynb`

Contains:

- Data preprocessing and EDA
- Bagging implementation
- Boosting (AdaBoost / Gradient Boosting)
- Stacked Ensemble model
- Hyperparameter tuning using 5-Fold CV
- Model comparison and evaluation

### 🔹 `datasets/`

- Wisconsin Breast Cancer Dataset
- 569 samples, 30 features
- Binary classification (Malignant / Benign)

### 🔹 `screenshots/`

- Ensemble model comparison
- Confusion matrices
- ROC curves
- Cross-validation results

---

## ▶️ How to Run the Experiment

Same as Exp 6 👇

```bash
git clone https://github.com/<your-username>/<repository-name>.git
cd <repository-name>
pip install -r requirements.txt
jupyter notebook
```

Run `Experiment_7.ipynb`.

---

## 📊 Output

- Accuracy, Precision, Recall, F1-score
- Confusion Matrix
- ROC Curve & AUC
- Cross-validation results
- Comparison of ensemble models

---

## 📈 Models Implemented

- **Bagging**
  - Decision Tree as base estimator
  - Bootstrap sampling

- **Boosting**
  - AdaBoost
  - Gradient Boosting

- **Stacked Ensemble**
  - Base Models: SVM, Naive Bayes, Decision Tree
  - Meta Learner: Logistic Regression

---

## 🎯 Learning Outcomes

- Understood **variance reduction (Bagging)**
- Learned **bias reduction (Boosting)**
- Implemented **stacking with meta-learning**
- Compared ensemble strategies
- Observed improvement over single models

---

## 👤 Author

**Name:** Priya Verma
**Course:** Machine Learning Algorithms Laboratory (Semester VI)
**Experiment:** 7 – Ensemble Learning
