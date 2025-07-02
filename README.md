# Bank Churn Prediction Using Machine Learning

A Python-based machine learning project predicting customer churn for banks using multiple classification models and data-driven insights to improve customer retention strategies.

## Overview

This project analyzes customer data to predict churn, helping banks identify customers likely to leave and proactively improve retention. Using Logistic Regression, Decision Trees, Random Forest, XGBoost, and Support Vector Machines, the project compares model performances and extracts actionable insights for stakeholders.

## Features

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Model training with multiple classification algorithms
- Model evaluation and comparison using accuracy, precision, recall, and F1-score
- Feature importance analysis
- Insights for customer retention

## Technologies Used

- Python
- Pandas
- NumPy
- scikit-learn
- XGBoost
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset

The project uses a bank churn dataset containing customer demographic details, account balance, tenure, and transaction activity to predict churn labels.

## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/bank-churn-prediction.git
    cd bank-churn-prediction
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
    Open the notebook and run all cells to view outputs and visualizations.

## Results

- Achieved high accuracy and balanced precision-recall using Random Forest and XGBoost.
- Identified key churn indicators including tenure, balance, and transaction activity.
- Developed interpretable visual insights for non-technical stakeholders.

## Future Improvements

- Hyperparameter tuning for optimal performance.
- Integration with Flask or Streamlit for a user-facing churn prediction dashboard.
- Testing on additional banking datasets for generalizability.


