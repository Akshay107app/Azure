# Azure_Synapse-Analytics

# Credit Card Fraud Detection

## Context

It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.

## Content

The dataset consists of credit card transactions made by European cardholders in September 2013. It includes transactions from a span of two days, during which there were 492 cases of fraud out of a total of 284,807 transactions. This means that the dataset is highly imbalanced, as fraudulent transactions (the positive class) make up only 0.172% of all transactions.

All the input features in this dataset are numerical and have been transformed using Principal Component Analysis (PCA) to protect confidentiality. As a result, the original features and additional background information cannot be shared. The dataset includes features labeled V1, V2, … V28, which represent the principal components obtained through PCA. However, two features, 'Time' and 'Amount,' were not transformed using PCA.

- The **'Time'** feature records the number of seconds that have passed between each transaction and the first transaction in the dataset.
- The **'Amount'** feature indicates the amount of money involved in each transaction. This feature can be useful for approaches that take into account the cost of individual transactions.
- The **'Class'** feature is the target variable, where a value of 1 indicates a fraudulent transaction, and 0 indicates a non-fraudulent transaction.
- 
Given the significant imbalance in the dataset, it is recommended to evaluate the model's performance using the Area Under the Precision-Recall Curve (AUPRC), as traditional accuracy metrics, like the confusion matrix, may not provide meaningful insights in such unbalanced scenarios.


### API Command to Download Dataset

kaggle datasets download -d mlg-ulb/creditcardfraud


[Dataset URL](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
