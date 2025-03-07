# Credit Card Fraud Detection Project

## About
This project is a mini-project for SC1015 (Introduction to Data Science and AI) focusing on credit card fraud detection. We utilized a credit card fraud dataset from Kaggle containing anonymized transactions labeled as fraudulent or genuine.

## Contributors
- Arpita: Exploratory Data Analysis
- Chavi: Analysis, Oversampling, and Validation
- Samriddhi: Machine Learning, Undersampling, and Classifiers

Before submission, we divided our dataset into three parts. You can find the code for this process in the GitHub repository link provided below. Additionally, we have included the Python code and the segmented Python code in three parts. However, for seamless execution, these parts need to be consolidated into the main credit card notebook.

## Problem Definition
We aim to develop a machine learning model capable of accurately detecting fraudulent credit card transactions to prevent unauthorized charges and financial losses. Our primary focus is on detecting frauds rather than non-frauds, which we highlighted in sampling techniques for handling class imbalance.

## Data Used
We utilized the credit card fraud dataset from Kaggle, which consists of anonymized credit card transactions labeled as fraudulent or genuine.

## Methodology
### Exploratory Data Analysis (EDA):
- Analyzed the dataset's characteristics, including transaction time, PCA-transformed features, and transaction amounts.
- Identified class imbalance, with only 0.17% of transactions labeled as fraudulent.

### Algorithmic Optimization:
- Explored dimensionality reduction techniques such as t-SNE, PCA, and truncated SVD.
- Experimented with classifiers including K-nearest neighbors, logistic regression, decision tree, and SVC.

### Machine Learning:
- Evaluated classifiers using cross-validation and grid search.
- Selected logistic regression as the best-performing model based on ROC-AUC score.
- Utilized logistic regression for final predictions due to its superior performance.

## Outcome
Achieved a high ROC-AUC score of 0.98 with logistic regression, indicating effective fraud detection. Identified key variables (V10, V12, V14, V17) contributing to model performance and explored sampling techniques and their impact on model performance.

## Video

Please note that this video has been compressed to be added here and the actual submitted version was of a much better quality.

https://github.com/Samsriddhi/creditcard-fraud-detection/assets/154321347/a1270d2b-2c39-4751-ac35-f654fe9125a5



## Insights and Recommendations
- Addressed class imbalance through undersampling, significantly improving model performance.
- Logistic regression demonstrated superior performance compared to other classifiers.
- Further exploration could include outlier removal and additional sampling techniques like SMOTE.

## References
- Kaggle: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
- Reference 1: https://medium.com/@corymaklin/synthetic-minority-over-sampling-technique-smote-7d419696b88c
- Reference 2: https://towardsdatascience.com/top-10-binary-classification-algorithms-a-beginners-guide-feeacbd7a3e2
- Reference 3: https://stackoverflow.com/questions/66120039/undersampling-before-or-after-train-test-split
- Reference 4: https://arxiv.org/abs/1106.1813
- Research Paper: https://arxiv.org/abs/2404.07356
