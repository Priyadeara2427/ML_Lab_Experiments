# Machine Learning Algorithms Laboratory

**UCS2612 – ML Lab (Semester VI)**

---

## 📘 Repository Overview

This repository contains the complete set of experiments performed as part of the **Machine Learning Algorithms Laboratory (UCS2612)** course.
Each experiment is organized in a **separate subfolder** with its own Jupyter Notebook, datasets, screenshots, and experiment-specific documentation.

The experiments cover **data preprocessing, exploratory data analysis (EDA), regression, classification, regularization, hyperparameter tuning, and model evaluation** using standard machine learning techniques.

---

## 🎯 Objectives of the Laboratory

- Gain hands-on experience with **Python-based machine learning tools**
- Understand the **end-to-end machine learning pipeline**
- Implement and evaluate **classification and regression models**
- Analyze **overfitting, underfitting, and bias–variance trade-offs**
- Apply **hyperparameter tuning and cross-validation**
- Visualize and interpret model performance

---

## 🛠️ Tools & Technologies Used

- **Python 3.x**
- **NumPy** – Numerical computing
- **Pandas** – Data manipulation and preprocessing
- **Matplotlib & Seaborn** – Data visualization
- **SciPy** – Scientific and statistical computing
- **Scikit-learn** – Machine learning algorithms and evaluation
- **Jupyter Notebook** – Interactive development

_(Some experiments additionally use OpenCV, TensorFlow, PyTorch, and XGBoost.)_

---

## 📁 Repository Structure

```text
ML_Lab_Experiments/
│
├── Experiment_1/
│   ├── README.md
│   ├── requirements.txt
│   ├── Experiment_1.ipynb
│   ├── datasets/
│   ├── Img/
│   └── screenshots/
│
├── Experiment_2/
│   ├── README.md
│   ├── requirements.txt
│   ├── Experiment_2.ipynb
│   ├── datasets/
│   └── screenshots/
│
├── Experiment_3/
│   ├── README.md
│   ├── requirements.txt
│   ├── Experiment_3.ipynb
│   ├── datasets/
│   └── screenshots/
│
├── Experiment_4/
│   ├── README.md
│   ├── requirements.txt
│   ├── Experiment_4.ipynb
│   ├── datasets/
│   └── screenshots/
│
├── Experiment_5/
│   ├── README.md
│   ├── requirements.txt
│   ├── Experiment_5.ipynb
│   ├── datasets/
│   └── screenshots/
│
├── Experiment_6/
│   ├── README.md
│   ├── requirements.txt
│   ├── Experiment_6.ipynb
│   ├── datasets/
│   └── screenshots/
│
└── README.md   ← (This file)
```

---

## 🧪 List of Experiments

### 🔹 Experiment 1: Working with Python Packages

**(NumPy, Pandas, SciPy, Scikit-learn, Matplotlib)**

- Data preprocessing and EDA
- Visualization techniques
- Introduction to ML workflows

---

### 🔹 Experiment 2: Binary Classification using Naïve Bayes and KNN

- Naïve Bayes variants (Gaussian, Multinomial, Bernoulli)
- KNN classification
- Hyperparameter tuning (GridSearch & RandomizedSearch)
- KDTree vs BallTree comparison
- Bias–Variance analysis

---

### 🔹 Experiment 3: Regression Analysis using Linear and Regularized Models

- Linear Regression
- Ridge, Lasso, Elastic Net
- Hyperparameter tuning
- Overfitting and underfitting analysis
- Effect of regularization on coefficients

---

### 🔹 Experiment 4: Binary Classification using Logistic Regression and SVM

- Logistic Regression with L1 & L2 regularization
- SVM with Linear, Polynomial, RBF, and Sigmoid kernels
- Hyperparameter tuning
- Cross-validation
- Comparative model analysis

---

### 🔹 Experiment 5: Perceptron vs Multilayer Perceptron with Hyperparameter Tuning

- Implementation of Single-Layer Perceptron (PLA)
- Multilayer Perceptron (MLP) with hidden layers
- Image preprocessing and normalization
- Hyperparameter tuning (learning rate, optimizer, activation, batch size)
- Training convergence analysis
- PLA vs MLP performance comparison
- Confusion matrix and ROC evaluation

---

### 🔹Experiment 6: Decision Tree and Random Forest — Comparative Study

- Decision Tree classifier implementation
- Random Forest ensemble model
- Hyperparameter tuning using 5-Fold Cross-Validation
- Overfitting and generalization analysis
- Tree depth and feature importance study
- Model comparison using accuracy, precision, recall, F1-score
- ROC curve and confusion matrix analysis

## ▶️ How to Run the Experiments

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Priyadeara2427/ML_Lab_Experiments.git
cd ML_Lab_Experiments
```

### 2️⃣ Navigate to an Experiment Folder

```bash
cd Experiment_1
```

### 3️⃣ Install Required Packages

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Jupyter Notebook

```bash
jupyter notebook
```

Open the corresponding `Experiment_X.ipynb` file and run all cells sequentially.

---

## 📊 Outputs

Each experiment produces:

- Model evaluation metrics (Accuracy, Precision, Recall, F1, MAE, RMSE, R², etc.)
- Graphical visualizations (histograms, boxplots, scatter plots, ROC curves, heatmaps)
- Comparative tables and analysis

All outputs are stored in the respective **`screenshots/`** folders.

---

## 🎓 Learning Outcomes

- Practical understanding of ML algorithms
- Strong foundation in data preprocessing and EDA
- Ability to evaluate and compare ML models
- Experience with hyperparameter tuning and validation
- Improved interpretation of ML results

---

## 👤 Author

**Name:** Priya Verma
**Degree:** B.E. Computer Science & Engineering
**Semester:** VI
**Course:** Machine Learning Algorithms Laboratory (UCS2612)
**Institution:** Sri Sivasubramaniya Nadar College of Engineering

---

## 📌 Notes

- Each experiment folder is **self-contained**
- Refer to individual experiment `README.md` files for detailed explanations
- Repository is structured as per **academic lab submission standards**
