# README: Employee Attrition Prediction

## Overview
This project focuses on predicting employee attrition using advanced machine learning techniques. High attrition rates pose significant challenges for organizations, leading to increased recruitment costs, loss of institutional knowledge, and decreased morale. By predicting and understanding employee attrition, companies can devise strategies to retain valuable talent.


## Key Topics Discussed
1. Problem & Solution
2. Conceptual Model
3. Data Mining Solution
4. Data
5. Data Exploration
6. Data Preprocessing
7. Modeling
8. Evaluation Metrics
9. Evaluation
10. Final Model Selection
11. Deployment

## Problem & Solution
Employee turnover is a major challenge for many organizations. This project aims to predict whether a given employee will leave the company, using a classification approach with supervised learning.

## Conceptual Model
The objective is to predict employee attrition using various machine learning models, which include Decision Tree, Logistic Regression, SVM, Neural Networks, Naive Bayes, Random Forest, Gradient Boosting, XGBoost, and k-NN. Hyperparameter tuning was conducted to optimize the models.

## Data
The dataset, sourced from Kaggle, provides a comprehensive examination of employee attrition and its contributing factors. It includes 35 columns and 1470 rows, with the target variable being binary (Yes/No) for attrition.

## Data Exploration
Key correlations and insights from the data exploration phase include:
- Top 3 Highest Positive Correlations: Distance From Home, Number of Companies Worked, Monthly Rate
- Top 3 Highest Negative Correlations: Total Working Years, Job Level, Years In Current Role

## Data Preprocessing
Steps involved in data preprocessing:
1. Data Encoding
2. Feature Scaling
3. Data Balancing
4. Data Partitioning (train-test split)

## Modeling
Various supervised learning models were used, with hyperparameter tuning applied to enhance performance:
- Decision Tree
- Logistic Regression
- SVM
- Neural Networks
- Naive Bayes
- Random Forest
- Gradient Boosting
- XGBoost
- k-NN

## Evaluation Metrics
The models were evaluated based on:
- **Accuracy**: Measures correct predictions of both staying and leaving employees.
- **F1-Score**: Harmonic mean of precision (avoiding false attrition alarms) and recall (catching true cases of attrition).
- **Confusion Matrix**: Provides a detailed breakdown of correct and incorrect predictions.
- **Classification Report**: Summarizes precision, recall, and F1-score for each class.

## Results
The best model was an SVM with hyperparameter tuning, which achieved:
- **Accuracy**: 98%
- **F1-Score**: 0.98
- **Confusion Matrix**: High precision and recall for both classes, indicating robust performance.

## Deployment Plan
### Model Development
- Process employee data and finalize the XGBoost model.
- Export the model for deployment.

### Integration & Launch
- Choose a cloud or on-premises platform.
- Set up a secure API for model access.
- Implement authentication and encryption.

### Monitoring & Impact
- Ensure system scalability and load management.
- Implement monitoring, logging, and CI/CD for updates.
- Conduct staging tests and provide API documentation.

## Business Impact
- **Cost Efficiency**: Reduce hiring and training costs by predicting attrition.
- **Talent Retention**: Implement strategies to retain valuable employees.
- **Enhanced Employee Experience**: Improve the overall employee experience by addressing potential reasons for attrition.

For a detailed overview and visual representation, please refer to the attached presentation: [CIS 508 Employee Attrition Prediction.pdf](file-DjJ4CYaJe6nLClGK7DGj1Eb5).