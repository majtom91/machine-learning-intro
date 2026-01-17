# machine-learning-intro

Linear Regression on Synthetic Data: A Data Cleaning Experiment

This pr contains a small linear regression experiment conducted as part of a data science learning exercise.

The goal was to build a linear regression model, evaluate its performance using R² score, and observe how data cleaning decisions impact model results — even when working with synthetic or randomly generated data.

📌 Project Overview

Dataset size: ~205 rows

Dataset type: Synthetic

Model: Linear Regression (scikit-learn)

Evaluation metric: R² score

Two experiments were performed:

1. Model trained on a cleaned dataset (null handling, duplicate removal, outlier analysis)

2. Model trained on a less-cleaned dataset (outliers retained)

The results highlighted how preprocessing affects model behavior, even when the data contains little to no real signal.

🧪 Workflow

Exploratory Data Analysis (EDA)

Missing value handling

Duplicate removal

Outlier analysis

Label encoding for categorical features

Train/test split (80/20)

Model training using Linear Regression

Performance evaluation using R² score

📈 Key Takeaways

Data cleaning improves data quality, but it cannot create meaningful patterns when the data itself is random

Skipping preprocessing can significantly degrade model performance

Metrics like R² should be interpreted in context, especially with synthetic datasets

The modeling process matters as much as the final score