# 📈 Week 05 — Linear & Polynomial Regression: From sklearn to From-Scratch

This directory contains the **Week 05** lab work for the Machine Learning course at SRM University AP.

---

## 📝 Lab Overview

**Notebook**: Linear_Poly_Regression_Teaching_Notebook.ipynb

The lab covers linear and polynomial regression modeling, evaluation metrics, regularization techniques, hyperparameter tuning, validation schemes, gradient descent implementation from scratch, and regression diagnostics using the Cars24 used-car dataset:

| Topic | Description |
|---|---|
| **Data Preparation** | Categorical encoding, feature scaling (StandardScaler), and train/test splitting |
| **Linear Regression with scikit-learn** | Univariate regression (finding the line of best fit) and multivariate regression |
| **Regression Evaluation** | Calculating and interpreting ^2$ score and Adjusted ^2$ for multivariate models |
| **Polynomial Regression** | Non-linear modeling using PolynomialFeatures, polynomial degree expansion (^2$ to ^6$) |
| **Bias–Variance Tradeoff** | Diagnosing underfitting vs. overfitting across model complexity degrees |
| **Regularization Techniques** | Ridge (L2 penalty), Lasso (L1 feature selection & sparsity), and ElasticNet |
| **Hyperparameter Tuning** | Systematically tuning polynomial degree and regularization strength ($\alpha$) |
| **Validation Schemes** | Train/Validation/Test split and K-Fold Cross-Validation |
| **Hand-Coded Linear Regression** | Building Linear Regression from scratch with Batch Gradient Descent (weights, bias, learning rate, loss tracking) |
| **Feature Scaling in GD** | Demonstrating convergence stability and gradient step dynamics with vs. without scaling |
| **Statistical Modeling (statsmodels)** | OLS regression summary, coefficients, standard errors, t-statistics, and p-values |
| **Regression Assumptions** | Diagnosing Multicollinearity (VIF), Normality of Residuals (Q-Q plot & Shapiro-Wilk), and Homoskedasticity |

---

## 🛠️ Tech Stack

- **Language**: Python 3
- **Libraries**: NumPy, Pandas, Scikit-learn, Statsmodels, Matplotlib, Seaborn
- **Environment**: Jupyter Notebook / Google Colab

---

## 🚀 Run in Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aditya-forge/AdityaKumar_AP24110010333/blob/main/Week-05/Linear_Poly_Regression_Teaching_Notebook.ipynb)
