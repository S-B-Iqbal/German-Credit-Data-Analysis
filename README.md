# German-Credit-Data-Analysis

## Objective

The objective is to build a model that classifies whether a Transaction is fraudulent or not.


This file contains the workflow for **Usecase # 2 - Fraud or Not** . The current Jupyter Notebook highlights the following:

* Introduction
    * Background
    * Objective
* 1. Libraries Implemented
* 2. Data Collection
    * 2.1 Data Source
    * 2.2 Data Loading
    * 2.3 Data Cleansing
        * 2.3.1 Removal of NAN's
* 3. Exploratory Data Analysis
* 4. Feature Engineering
* 5. Data Modeling
    * 5.1 Data Preparation
        * 5.1.1 Assigning 'Dependent' and 'Independent' Features.
        * 5.1.2 Data Stadardization: Dummification of Categorical Columns and Normalization of Numerical Columns
        * 5.1.3 Dividing the Data into 'Train', 'Validation' and 'Test' Sets.
    * 5.2 Model Comparison
        - Various Models are assessed based on their Recall, Precision, ROC-AUC and Accuracy.
    * 5.3 Model Selection : Logistic Regression
    * 5.4 Model Optimization
        * 5.4.1 'l2' Regularized Model
        * 5.4.2 'l1' Regularized Model
    * 5.5 Model Evaluation
* 6. Results
* 7. Conclusion

## Background

The Dataset holds about a 1000 credit card transactions of users along with labels.

## Data Source

The Data Source for the current project is taken from the **Kaggle** repository with the following [Link](​https://www.kaggle.com/uciml/german-credit)

The original Dataset was missing the **default** column. I have added the column from the original UCI Repository.
Please refer the below link for further reference:

[Missing Credit Label](https://www.kaggle.com/uciml/german-credit/discussion/26658#latest-275345)
