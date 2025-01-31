# Credit Risk Classification

## Overview
This project aims to build a **logistic regression model** to predict the creditworthiness of borrowers based on historical lending data. The model evaluates whether a loan is **healthy (0)** or **high risk (1)**.

## Steps
1. **Preprocess the Data**
   - Load and clean the dataset.
   - Define the target variable (`loan_status`) and features.
   - Split data into **training** and **testing** sets.

2. **Train and Evaluate Logistic Regression Model**
   - Train a logistic regression model on the training data.
   - Make predictions on the test set.
   - Evaluate performance using:
     - **Confusion Matrix**
     - **Accuracy Score**
     - **Precision & Recall**

3. **Optimize the Model (if applicable)**
   - Address class imbalance using resampling techniques.
   - Compare performance before and after resampling.

4. **Write a Credit Risk Analysis Report**
   - Explain the purpose of the analysis.
   - Summarize model performance metrics.
   - Justify whether the model is suitable for use.

## Results
- **Balanced Accuracy Score:** 95.2%
- **Precision Score:** 92%
- **Recall Score:** 95%

## Recommendation
The model achieves **high accuracy (95%)** and is effective in predicting loan risk. Given its strong performance, it can be recommended for assessing borrower creditworthiness.

## Files
- `credit_risk_classification.ipynb` - Jupyter Notebook with model training and evaluation.
- `lending_data.csv` - Historical loan data.
- `README.md` - Project documentation.

## Tools Used
- **Python**
- **Pandas & Scikit-Learn** (Data preprocessing, model training)
- **Logistic Regression** (Classification model)
- **Matplotlib & Seaborn** (Data visualization)

## Submission
- All files are uploaded to the **credit-risk-classification** GitHub repository.
