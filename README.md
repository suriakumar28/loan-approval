# Loan Approval Prediction Using Machine Learning

## Introduction
Predicting loan approval status using machine learning algorithms is crucial for financial institutions to improve efficiency, minimize human error, and eliminate biases. This project leverages various personal and financial attributes such as gender, salary, credit score, and previous loan defaults to automate the loan approval process.

## Dataset
The dataset used in this study includes:
- Applicant's gender
- Salary
- Credit score
- Loan approval status
- Previous loan defaults
- Other relevant attributes

The dataset is a synthetic version inspired by the original **Credit Risk dataset from Kaggle**, enriched with additional financial risk-related variables.

## Project Workflow
1. **Data Preprocessing**
   - Handling missing values and imbalanced data
   - Encoding categorical variables
   - Outlier detection using boxplots
   - Feature selection using Random Forest

2. **Exploratory Data Analysis (EDA)**
   - Identifying trends and patterns
   - Visualizing data distributions

3. **Machine Learning Models**
   - XGBoost
   - Decision Tree
   - Naive Bayes
   - LightGBM
   - Random Forest

4. **Model Training & Evaluation**
   - Hyperparameter tuning using Grid Search CV & Random Search
   - K-fold cross-validation
   - Evaluation metrics: 
     - Accuracy
     - Precision
     - Recall
     - F1-score
     - AUC-ROC
     - Bootstrap Sampling
   - Learning curves & cumulative gain charts for model validation

## Key Findings
- The **LightGBM** model achieved the highest accuracy among all tested models.
- The model was validated to ensure fairness, preventing biases in loan approval decisions.

## Goal & Impact
- Improve accuracy and efficiency in loan approval predictions.
- Reduce biases in financial decision-making.
- Provide a **more equitable and fair** loan approval system for both lenders and borrowers.

## Tools & Technologies
- Python
- Scikit-learn
- XGBoost
- LightGBM
- Matplotlib & Seaborn (for visualization)
- Pandas & NumPy (for data processing)
