# Credit Card Fraud Detection Project

## About
This project is a mini-project for SC1015 (Introduction to Data Science and AI) focusing on credit card fraud detection. We utilized a credit card fraud dataset from Kaggle containing anonymized transactions labeled as fraudulent or genuine.

## Contributors
- Arpita
- Chavi
- Samriddhi

## Problem Definition
Can we accurately detect fraudulent credit card transactions using machine learning techniques? 

## Data Used
We utilized the credit card fraud dataset from Kaggle, which consists of anonymized credit card transactions labeled as fraudulent or genuine.

## Methodology
1. **Exploratory Data Analysis (EDA)**:
   - Analyzed the dataset's characteristics, including transaction time, PCA-transformed features, and transaction amounts.
   - Identified class imbalance, with only 0.17% of transactions labeled as fraudulent.

2. **Algorithmic Optimization**:
   - Explored dimensionality reduction techniques such as t-SNE, PCA, and truncated SVD.
   - Experimented with classifiers including K-nearest neighbors, logistic regression, decision tree, and SVC.

3. **Machine Learning**:
   - Evaluated classifiers using cross-validation and grid search.
   - Selected logistic regression as the best-performing model based on ROC-AUC score.

## Outcome
- Achieved a high ROC-AUC score of 0.98 with logistic regression, indicating effective fraud detection.
- Identified key variables (V10, V12, V14, V17) contributing to model performance.
- Explored sampling techniques and their impact on model performance.

## Insights and Recommendations
- Class imbalance was addressed through undersampling, significantly improving model performance.
- Logistic regression demonstrated superior performance compared to other classifiers.
- Further exploration could include outlier removal and additional sampling techniques like SMOTE.

## References
- Kaggle: [Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)
