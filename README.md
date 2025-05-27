# Supervised Machine Learning Regression – Black Friday Sales Predictions

This project focuses on predicting **purchase amounts** during Black Friday using various regression models. The dataset combines both **numerical** and **categorical** features and explores different modeling approaches to improve prediction accuracy.

---

## About the Dataset

The dataset contains historical sales data from a Black Friday event. It includes:

- Target: `Purchase` (amount spent)
- Numerical Features: product category scores, purchase history
- Categorical Features: age, gender, marital status, occupation

---

## Objective

- Build multiple **regression models** to predict the `Purchase` amount.
- Analyze and compare model performance using metrics like **RMSE** and **R²**.
- Explore feature relationships to maintain **interpretability**.

---

## Exploratory Data Analysis (EDA)

- Checked for **missing values** and cleaned data accordingly.
- Visualized distributions, relationships, and outliers.
- Encoded categorical features (if applicable).
- Conducted **feature engineering** including **polynomial features**.

---

## Models Trained

### 1. Simple Linear Regression
- Baseline model using raw, preprocessed features.
- Fast and interpretable, but lacks complexity.

### 2. Polynomial Regression (Degree 2)
- Captures **non-linear relationships** between features and `Purchase`.
- Achieved the **lowest RMSE** and **highest R² score** among models.

### 3. Ridge Regression
- Adds **L2 regularization** to reduce overfitting and multicollinearity.
- Coefficient shrinkage without feature elimination.

### 4. Lasso Regression
- Applies **L1 regularization** to enforce sparsity.
- Useful for feature selection, but did not outperform polynomial model.

---

## Recommended Final Model

**Polynomial Regression (Degree 2)**

- Best balance between **accuracy** and **interpretability**
- Captures complex, non-linear relationships in the data
- Coefficients provide insight into feature importance

---

## Key Findings

- Polynomial features significantly enhance model performance
- Regularization techniques (Ridge, Lasso) had **limited impact** in this case
- **Data cleaning and EDA** were crucial for meaningful modeling
- **Non-linear patterns** exist in Black Friday purchase behavior

---

## Technologies Used

- **Python**
- **Pandas, NumPy** for data wrangling
- **Matplotlib, Seaborn** for visualizations
- **Scikit-learn** for model building and evaluation




