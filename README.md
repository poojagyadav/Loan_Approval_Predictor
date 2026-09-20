# Loan Approval Predictor

This project analyzes loan approval patterns and builds a predictive model to estimate whether a loan application is likely to be approved based on applicant characteristics and financial indicators.

## Project Overview

The repository contains:

- `credit_wise.ipynb` — exploratory data analysis (EDA), preprocessing, and model-building workflow
- `loan_approval_data.csv` — dataset used for analysis and prediction

The goal is to examine relationships between applicant details such as income, credit score, debt-to-income ratio, savings, and employment status, and predict the `Loan_Approved` outcome.

## Dataset

The dataset is stored in `loan_approval_data.csv` and includes fields such as:

- Applicant ID
- Applicant income and co-applicant income
- Employment status
- Age and marital status
- Dependents
- Credit score
- Existing loans
- DTI ratio
- Savings
- Collateral value
- Loan amount and term
- Loan purpose and property area
- Education level and gender
- Employer category
- Target variable: `Loan_Approved`

## Notebook

Open and run `credit_wise.ipynb` in Jupyter Notebook or VS Code with the Jupyter extension.

The notebook typically covers:

- Loading the dataset
- Cleaning missing or inconsistent values
- Exploring distributions and relationships
- Selecting relevant features
- Training a classification model
- Evaluating model performance
- Interpreting the results

## Requirements

To run this project, install the following Python packages:

```bash
pip install jupyter pandas numpy matplotlib seaborn scikit-learn
```

It is recommended to use Python 3.9+.

## How to Run

1. Open the project folder.
2. Start Jupyter Notebook or VS Code Notebook environment.
3. Open `credit_wise.ipynb`.
4. Run all cells in order.
5. Review the output, model metrics, and insights from the analysis.

## Project Structure

```text
Loan_Approval_Predictor/
├── README.md
├── credit_wise.ipynb
├── loan_approval_data.csv
```

## Notes

- This project is intended for learning, analytics, and predictive modeling practice.
- The dataset may be synthetic or example-based, depending on the source.
- You can extend the workflow by experimenting with additional models, feature engineering, or hyperparameter tuning.

