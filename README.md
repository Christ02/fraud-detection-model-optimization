# Credit Card Fraud Detection with Decision Trees and SVM

## Project Overview

This repository contains a Jupyter notebook (`decision_tree_svm_ccFraud.ipynb`) that implements a credit-card fraud-detection system using two classification models:

1. **Decision Tree**
2. **Support Vector Machine (SVM)**

The project tackles a highly imbalanced dataset in which only 0.172 % of all transactions are fraudulent, showcasing techniques for handling class imbalance and evaluating anomaly-detection models.

## Repository Contents

* `decision_tree_svm_ccFraud.ipynb` – the main notebook with the full analysis
* `README.md` – this documentation file

## Key Features

* **Data preprocessing** – feature scaling and normalization
* **Class-imbalance handling** – class-weighting to boost the minority class impact
* **Modeling** – Decision Tree and SVM implementations with scikit-learn
* **Evaluation** – performance metrics tailored to imbalanced datasets (e.g., AUC-ROC)
* **Visualization** – plots to inspect class distribution and feature correlations

## Requirements

To run the notebook you’ll need:

* Python 3.x
* Jupyter Notebook

Python libraries:

```bash
pip install pandas scikit-learn matplotlib numpy jupyter
```

## How to Use

1. Clone this repository.
2. Open the Jupyter notebook `decision_tree_svm_ccFraud.ipynb`.
3. Run the cells in order to:

   * Load and explore the data
   * Preprocess the features
   * Train the models
   * Evaluate their performance

## Highlights

The notebook provides a side-by-side comparison of both models, including:

* Training times
* Evaluation metrics (such as AUC-ROC)
* Feature-importance interpretation

## Dataset

The dataset used is Kaggle’s **“Credit Card Fraud Detection”**, which contains transactions made by European cardholders in September 2013.

Dataset link: [Credit Card Fraud Detection on Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud)
