# Experiment 3: Regression Analysis using Linear and Regularized Models

**(Linear Regression, Ridge, Lasso, Elastic Net)**

---

## 📌 Objective

The objective of this experiment is to implement **linear and regularized regression models** to predict a continuous target variable. The experiment focuses on evaluating model performance using multiple regression metrics, visualizing regression behavior, and analyzing **overfitting, underfitting, and bias–variance trade-offs**.

---

## 🛠️ Tools & Libraries Used

The following Python libraries are used in this experiment:

- **NumPy** – Numerical computations and array operations
- **Pandas** – Data loading, cleaning, and preprocessing
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualizations
- **Scikit-learn** –
  - Linear Regression
  - Ridge, Lasso, and Elastic Net
  - Feature scaling and encoding
  - Hyperparameter tuning (GridSearchCV / RandomizedSearchCV)
  - Regression evaluation metrics

- **Jupyter Notebook** – Interactive execution and documentation

---

## 📁 Repository Structure

```text
├── README.md
├── requirements.txt
├── Experiment_3.ipynb
├── datasets/
│   └── loan_data.csv
├── screenshots/
│   ├── target_distribution.png
│   ├── feature_vs_target.png
│   ├── predicted_vs_actual.png
│   ├── residual_plot.png
│   ├── train_vs_validation_error.png
│   └── coefficient_comparison.png
```

---

## 📂 Description of Files and Folders

### 🔹 `README.md`

Provides an overview of the experiment, tools used, repository structure, execution steps, and learning outcomes.

### 🔹 `Experiment_3.ipynb`

Jupyter Notebook containing the complete implementation, including:

- Dataset loading and preprocessing
- Exploratory Data Analysis (EDA)
- Baseline Linear Regression model
- Regularized regression models:
  - Ridge Regression
  - Lasso Regression
  - Elastic Net Regression

- Hyperparameter tuning using cross-validation
- Model evaluation and visualization

### 🔹 `datasets/`

Contains the dataset used in this experiment:

- **Loan Amount Prediction Dataset** (continuous target variable)

### 🔹 `screenshots/`

Contains screenshots of output visualizations generated during execution, including:

- Target variable distribution
- Feature vs target scatter plots
- Predicted vs actual values plot
- Residual plots
- Training vs validation error plots
- Coefficient comparison bar plot

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

Open `Experiment_3.ipynb` and run all cells sequentially.

---

## 📊 Output

The experiment generates:

- Regression performance metrics:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R² Score
  - Training Time

- Visualizations for:
  - Target variable distribution
  - Predicted vs actual values
  - Residual analysis
  - Training vs validation error
  - Effect of regularization on coefficients

- Comparative tables for:
  - Linear vs regularized models
  - Hyperparameter tuning results
  - Cross-validation and test set performance

All output visualizations are saved in the `screenshots/` folder.

---

## 📈 Models Implemented

- **Linear Regression** (Baseline)
- **Ridge Regression**
- **Lasso Regression**
- **Elastic Net Regression**

Hyperparameter tuning is performed using **5-Fold Cross-Validation** to identify optimal regularization strength.

---

## 🎯 Learning Outcomes

- Implemented linear and regularized regression models
- Understood the effect of regularization on model complexity
- Analyzed overfitting and underfitting in regression models
- Studied bias–variance trade-offs in linear models
- Compared coefficient behavior across Ridge, Lasso, and Elastic Net
- Evaluated regression models using standard performance metrics
- Visualized regression errors and predictions

---

## 👤 Author

**Name:** Priya Verma
**Course:** Machine Learning Algorithms Laboratory (Semester VI)
**Experiment:** 3 – Regression Analysis using Linear and Regularized Models
