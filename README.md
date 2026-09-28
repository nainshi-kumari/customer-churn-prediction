# Customer Churn Prediction Using Machine Learning

## Project Overview

This project focuses on predicting customer churn using machine learning classification techniques. The objective is to identify customers who are likely to leave a service based on their demographic, service usage, contract, and billing-related information.

## Dataset

The project uses the Telco Customer Churn dataset containing customer information and their churn status.

## Machine Learning Models

The following classification models were implemented:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

## Data Preprocessing

The preprocessing steps included:

- Handling categorical variables
- Encoding categorical features
- Converting numerical features
- Train-test splitting
- Feature scaling for Logistic Regression

## Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## Results

| Model | Accuracy | Precision | Recall | F1 Score |
|---|---:|---:|---:|---:|
| Logistic Regression | 80.70% | 65.84% | 56.68% | 60.92% |
| Decision Tree | 79.42% | 63.13% | 54.01% | 58.21% |
| Random Forest | 80.27% | 67.27% | 50.00% | 57.36% |

## Feature Importance

Random Forest feature-importance analysis was performed to understand which features contributed most to the model's predictions.

Some of the important features included:

- Tenure
- Total Charges
- Monthly Charges
- Internet Service
- Contract Type
- Payment Method

## Prediction Demo

The trained Logistic Regression model was also used to predict churn for an individual customer.

Example:

**Prediction:** Customer is likely to stay  
**Churn Probability:** 4.5%

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab
- Jupyter Notebook

## Key Learning Outcomes

Through this project, I practiced:

- Data preprocessing
- Feature engineering
- Classification algorithms
- Model evaluation
- Confusion matrix analysis
- Feature importance
- Customer churn prediction
