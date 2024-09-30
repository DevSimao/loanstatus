# Loan Approval Prediction Using Machine Learning
This project aims to predict loan approval status based on various applicant attributes using machine learning techniques. The model takes input from different features like applicant income, credit history, and loan amount to predict whether a loan application will be approved (1) or not (0).

# Project Overview
Loan approval is a critical process for financial institutions, and using machine learning can help streamline this process by analyzing patterns in applicant data. This project uses a dataset of loan applications to train and evaluate models that can predict loan status.

# Data Dictionary
The data has the following fields:

|Column name | Description |
|------------|-------------|
| `loan_id`  | Unique loan id |
| `gender`   | Gender - `Male` / `Female` |
| `married`  | Marital status - `Yes` / `No` |
| `dependents` | Number of dependents |
| `education` | Education - `Graduate` / `Not Graduate` |
| `self_employed` | Self-employment status - `Yes` / `No` |
| `applicant_income` | Applicant's income |
| `coapplicant_income` | Coapplicant's income |
| `loan_amount` | Loan amount (thousands) |
| `loan_amount_term` | Term of loan (months) |
| `credit_history` | Credit history meets guidelines - `1` / `0` |
| `property_area` | Area of the property - `Urban` / `Semi Urban` / `Rural` | 
| `loan_status` | Loan approval status (target) - `1` / `0` |

Objective
The goal of this project is to build a model that can predict loan approval status based on the given features. The project explores various machine learning algorithms and evaluates their performance using appropriate metrics.

# Getting Started
## Prerequisites
To run this project, you will need the following:
- Python 3.x
- Jupyter Notebook or any IDE of your choice
- Libraries:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn
 
# Dataset
The dataset used in this project contains information about applicants and their corresponding loan statuses. You can find the dataset in the `data` directory.

# Data Preprocessing
Before building the machine learning model, the data needs to be preprocessed. Key steps include:
- Checking for and handling missing values.
- Encoding categorical variables (e.g., gender, married, education)
- Scaling numerical variables (e.g., applicant_income, loan_amount)

# Model Building
- Logistic Regression

# Evaluation Metrics
To assess the performance of the model, the following metrics are used:
- Accuracy
- Precision
- Recall

# Results
The machine learning models are trained and tested on the dataset, and the results are analyzed based on the evaluation metrics. Key findings and model performance are documented in the Jupyter notebook.

# Conclusion
This project demonstrates the use of machine learning to predict loan approval status based on applicant data. By analyzing features like income, credit history, and loan amount, the model can help financial institutions make more informed decisions on loan applications.

# Future Work
Further improvements could include:
- Tuning hyperparameters for better model performance
- Using other models and advanced algorithms
- Gathering more data for better model generalization
