# Classification Model Comparison Project

## Overview

This repository contains Jupyter notebooks for comparing different classification algorithms on a dataset, evaluating their performance, and applying explainable AI techniques (SHAP) to interpret model predictions.

## Notebooks

* **main\_nootebook.ipynb**

  * Performs exploratory data analysis (EDA)
  * Preprocessing and feature engineering
  * Baseline model training (e.g., Logistic Regression)
  * Evaluation metrics: ROC curve, AUC, classification report

* **gb\_testing.ipynb**

  * Trains and compares multiple classifiers (KNN, Logistic Regression, XGBoost, Random Forest)
  * Hyperparameter tuning examples
  * Detailed performance comparison using confusion matrices and ROC/AUC
  * Applies SHAP to the best-performing model for interpretability

## Installation

1. Clone the repository:

   ```bash
   git clone <repository_url>
   cd <repository_folder>
   ```
2. (Optional) Create and activate a virtual environment:

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

> **Note:** A sample `requirements.txt` might include:
>
> ```text
> pandas
> numpy
> scikit-learn
> seaborn
> matplotlib
> xgboost
> shap
> ```

## Usage

1. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```
2. Open and run the cells in each notebook in order.
3. Review outputs: performance metrics, plots, and SHAP explanations.

## Contributing

Feel free to open issues or submit pull requests to improve the analysis, add more models, or enhance visualizations.