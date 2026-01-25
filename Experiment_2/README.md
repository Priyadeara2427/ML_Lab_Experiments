# Experiment 2: Binary Classification using Naïve Bayes and K-Nearest Neighbors

**(Naïve Bayes, KNN, Hyperparameter Tuning, KDTree, BallTree)**

---

## 📌 Objective

The objective of this experiment is to implement and compare **Naïve Bayes** and **K-Nearest Neighbors (KNN)** classifiers for a binary classification problem. The experiment focuses on evaluating model performance using multiple metrics, tuning hyperparameters, visualizing model behavior, and analyzing **overfitting, underfitting, and bias–variance trade-offs**.

---

## 🛠️ Tools & Libraries Used

The following Python libraries are used in this experiment:

- **NumPy** – Numerical computations
- **Pandas** – Dataset loading and preprocessing
- **Matplotlib** – Visualization of results
- **Seaborn** – Statistical visualizations
- **Scikit-learn** –
  - Naïve Bayes classifiers
  - KNN classifier
  - Hyperparameter tuning (GridSearchCV, RandomizedSearchCV)
  - Performance metrics

- **Jupyter Notebook** – Interactive execution and documentation

---

## 📁 Repository Structure

```text
├── README.md
├── requirements.txt
├── Experiment_2.ipynb
├── datasets/
│   └── spambase.csv
├── screenshots/
│   ├── class_distribution.png
│   ├── confusion_matrix_nb.png
│   ├── confusion_matrix_knn.png
│   ├── roc_curve_nb.png
│   ├── roc_curve_knn.png
│   ├── accuracy_vs_k.png
│   └── train_vs_validation_accuracy.png
```

---

## 📂 Description of Files and Folders

### 🔹 `README.md`

Provides a detailed overview of the experiment, tools used, repository structure, execution steps, and learning outcomes.

### 🔹 `Experiment_2.ipynb`

Jupyter Notebook containing the complete implementation, including:

- Dataset loading and preprocessing
- Exploratory Data Analysis (EDA)
- Naïve Bayes classifiers:
  - Gaussian Naïve Bayes
  - Multinomial Naïve Bayes
  - Bernoulli Naïve Bayes

- KNN baseline model
- Hyperparameter tuning using:
  - GridSearchCV
  - RandomizedSearchCV

- KDTree vs BallTree neighbor search comparison
- Performance evaluation and visualization

### 🔹 `datasets/`

Contains the dataset used in this experiment:

- **Spambase Dataset** (binary classification: spam / not spam)

### 🔹 `screenshots/`

Contains screenshots of outputs generated during execution, including:

- Class distribution plots
- Confusion matrices
- ROC curves
- Accuracy vs k plots
- Training vs validation accuracy plots

### 🔹 `requirements.txt`

Lists all required Python libraries to ensure reproducibility.

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

Open `Experiment_2.ipynb` and run all cells sequentially.

---

## 📊 Output

The experiment generates:

- Performance metrics:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - Specificity
  - False Positive Rate
  - Training Time
  - Prediction Time

- Confusion matrices for each classifier
- ROC curves for Naïve Bayes and KNN
- Accuracy vs k plot for KNN
- Training vs validation accuracy plots
- Comparative tables for:
  - Naïve Bayes variants
  - Grid Search vs Randomized Search
  - KDTree vs BallTree

All output visualizations are saved in the `screenshots/` folder.

---

## 📈 Models Implemented

- **Naïve Bayes**
  - Gaussian NB
  - Multinomial NB
  - Bernoulli NB

- **K-Nearest Neighbors (KNN)**
  - Baseline KNN
  - Optimized KNN using GridSearchCV
  - Optimized KNN using RandomizedSearchCV
  - KDTree and BallTree search strategies

---

## 🎯 Learning Outcomes

- Implemented Naïve Bayes and KNN classifiers for binary classification
- Understood the importance of feature scaling in distance-based models
- Performed hyperparameter tuning using Grid Search and Randomized Search
- Compared KDTree and BallTree neighbor search algorithms
- Analyzed overfitting and underfitting behavior
- Studied bias–variance trade-offs in probabilistic and instance-based models
- Evaluated models using multiple performance metrics
- Visualized classifier performance using plots and confusion matrices

---

## 👤 Author

**Name:** Priya Verma
**Course:** Machine Learning Algorithms Laboratory (Semester VI)
**Experiment:** 2 – Binary Classification using Naïve Bayes and KNN
