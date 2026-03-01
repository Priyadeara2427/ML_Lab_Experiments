# Experiment 5: Perceptron vs Multilayer Perceptron with Hyperparameter Tuning

**(Single-Layer Perceptron vs Multilayer Neural Network)**

---

## 📌 Objective

The objective of this experiment is to implement and compare the performance of:

- **Model A:** Single-Layer Perceptron Learning Algorithm (PLA)
- **Model B:** Multilayer Perceptron (MLP) with hidden layers and nonlinear activation functions

The experiment focuses on understanding the impact of **hyperparameter tuning, optimizer selection, activation functions, and network architecture** on classification performance for handwritten character recognition.

---

## 🛠️ Tools & Libraries Used

The following Python libraries are used:

- **NumPy** – Numerical computations

- **Pandas** – Data preprocessing

- **Matplotlib** – Visualization

- **Seaborn** – Statistical plots

- **Scikit-learn** –
  - Perceptron / MLP implementation
  - Model evaluation metrics
  - Confusion matrix and ROC curves

- **Jupyter Notebook** – Interactive execution

---

## 📁 Repository Structure

```text
├── README.md
├── requirements.txt
├── Experiment_5.ipynb
├── Lab_Report_Exp5.pdf
├── datasets/
│   ├── english.csv/
│   └── Img
│       └── img001-001.png
├── screenshots/
│   ├── confusion.png
│   ├── ROC.png
│   └── lossVsEpochs.png
```

---

## 📂 Description of Files and Folders

### 🔹 `README.md`

Provides experiment overview, tools used, execution steps, and learning outcomes.

### 🔹 `Experiment_5.ipynb`

Contains complete implementation:

- Dataset preprocessing (resize, flatten, normalize)
- Implementation of Perceptron Learning Algorithm
- One-vs-Rest multi-class classification
- Multilayer Perceptron model
- Hyperparameter tuning:
  - Learning rate
  - Hidden layers
  - Batch size
  - Activation function
  - Optimizer (SGD, Adam)

- Model comparison and evaluation

### 🔹 `datasets/`

Contains:

- **English Handwritten Characters Dataset** from Kaggle
- 3410 grayscale character images
- 62 classes (0–9, A–Z, a–z)

### 🔹 `screenshots/`

Contains output visualizations:

- Confusion matrices
- ROC curves
- Training loss curves

### 🔹 `requirements.txt`

Lists required Python packages.

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

Open `Experiment_5.ipynb` and run all cells.

---

## 📊 Output

The experiment generates:

- Accuracy, Precision, Recall, F1-score
- Confusion matrices
- ROC curves (micro/macro)
- Training loss vs epochs
- Hyperparameter tuning results
- PLA vs MLP comparison

---

## 📈 Models Implemented

- **Perceptron Learning Algorithm**
  - Step activation
  - One-vs-Rest classification
  - Linear decision boundary

- **Multilayer Perceptron (MLP)**
  - Hidden layers with nonlinear activation
  - ReLU / Tanh / Sigmoid activation
  - SGD and Adam optimizers
  - Backpropagation training

---

## 🎯 Learning Outcomes

- Implemented linear and nonlinear classifiers
- Understood limitations of single-layer perceptron
- Learned neural network architecture design
- Applied hyperparameter tuning for deep learning models
- Compared model convergence and performance
- Studied overfitting and generalization in neural networks

---

## 👤 Author

**Name:** Priya Verma
**Course:** Machine Learning Algorithms Laboratory (Semester VI)
**Experiment:** 5 – Perceptron vs Multilayer Perceptron

---
