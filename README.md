# machine-learning-lab

A collection of machine learning implementations and analyses completed during my Master's degree lab course. All implementations are built from scratch using NumPy, PyTorch, and Matplotlib (no scikit-learn for core algorithms, per course requirements).

## 📋 Overview

This repository demonstrates practical implementations of fundamental and advanced machine learning algorithms, covering:

- **Statistical Analysis** — Descriptive statistics, correlation, hypothesis testing
- **Optimization** — Gradient descent, Newton's method, SGD, coordinate descent
- **Regression** — Linear, logistic, regularized (L1/L2), time series
- **Classification** — SVM, KNN, decision trees, MLP
- **Unsupervised Learning** — PCA, PPCA, Kernel PCA, association rule mining
- **Deep Learning** — Transformer-based text generation (PyTorch)

## 🗂️ Projects

| # | Topic | Key Techniques | Link |
|---|-------|---------------|------|
| 01 | Statistics & Visualization | Mean, std, histograms, correlation from scratch | [→](01 Statistics & Visualization/) |
| 02 | Gradient Descent Optimization | Booth function, adaptive step length | [→](./02 gradient-descent/) |
| 03 | Linear & Logistic Regression | Newton's method, MSE, cross-entropy | [→](./03-linear-logistic-regression/) |
| 04 | Regularization & SGD | L1/L2 regularization, AIC feature selection, K-fold CV | [→](./04-regularization-sgd/) |
| 05 | KNN & Decision Trees | KNN imputation, KNN classifier, tree regression | [→](./05-knn-and-decision-trees/) |
| 06 | SVM & Imbalanced Learning | Submanifold minimization, SMOTE, Pegasos | [→](./06-svm-and-imbalanced-learning/) |
| 07 | Association Rules | Apriori, Eclat, market basket analysis | [→](./07-association-rules/) |
| 08 | Dimensionality Reduction | PCA imputation, PPCA-EM, Kernel PCA | [→](./08-dimensionality-reduction/) |
| 09 | Transformer Text Generator | Multi-head attention, causal masking, PyTorch | [→](./09-transformer-text-generator/) |
| 10 | Time Series Regression | Linear regression on time series, 3D visualization | [→](./10-time-series-regression/) |

## 🛠️ Tech Stack

- **Python 3.x**
- **NumPy** — Core numerical operations
- **Pandas** — Data manipulation
- **Matplotlib / Seaborn** — Visualization
- **PyTorch** — Neural networks & Transformers
- **SciPy** — Optimization utilities
- **Jupyter** — Interactive analysis

## 🚀 Getting Started

```bash
git clone https://github.com/JohnPaulo-code/machine-learning-lab.git
cd machine-learning-lab
pip install -r requirements.txt
