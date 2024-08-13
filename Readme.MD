🔍 Project Title: Credit Card Fraud Detection with Azure Synapse and Power BI
💡 Summary: Developed a comprehensive solution for detecting fraudulent credit card transactions using Azure Synapse Analytics and Power BI. Implemented ONNX regression models for real-time predictions and created interactive dashboards for stakeholders to visualize and act on insights.

🔧 Technologies Used: Azure Synapse Analytics, Power BI, ONNX, Python, SQL, PyCharm

🚀 Project Highlights:

Designed and executed a data pipeline in Azure Synapse Analytics for processing transaction data.
Integrated ONNX regression models to accurately predict potential fraudulent activities.
Created dynamic Power BI dashboards to visualize trends and provide actionable insights for fraud prevention.

📈 **Results**:
Achieved a 30% reduction in false positives, enhancing the accuracy of fraud detection.
Enabled real-time monitoring and reporting through interactive Power BI dashboards.
1. Project Overview
# 1. Overview of the Project

## Credit Card Fraud Detection using Azure Synapse Analytics and PCA

## Overview
In recent years, unauthorized use of credit cards, particularly in mail orders and online transactions where the physical card is not presented to the vendor, has surged globally. Without effective countermeasures, this trend poses significant risks and could lead to substantial financial losses for both credit card users and companies.

## The Challenge for Businesses
To combat unauthorized use, it is vital to accurately predict and detect fraudulent transactions based on transaction details. Quick identification of such unauthorized transactions has become a pressing concern for credit card companies and financial institutions.

These organizations must swiftly understand and analyze trends in fraudulent spending over time and assess the geographical characteristics of unauthorized use. Additionally, they need to develop concrete measures to prevent such activities.

## Objectives and Goals
The project aims to utilize Azure Synapse Analytics' SQL On-Demand feature to transform credit card fraud detection and geographical data stored in CSV format within Azure Data Lake Storage Gen2. This transformation occurs without the need for extensive programming. Furthermore, the project demonstrates how to perform advanced data analysis using Power BI reports.

# 2. About Principal Component Analysis (PCA)

## About Principal Component Analysis (PCA)
Principal Component Analysis (PCA) is a widely used dimensionality reduction technique in machine learning. It simplifies datasets by transforming the original variables into a set of uncorrelated components, each explaining a portion of the total variance.

### Application of PCA in this Project
In this project, PCA is employed to reduce the dimensionality of the dataset, which comprises 28 principal components. The original features, including personal information such as names, store details, and products purchased, are excluded from the dataset to comply with GDPR and protect individual privacy. By retaining only the components that capture the most significant variance, PCA helps enhance the performance of the machine learning models by minimizing noise and reducing the risk of overfitting.


PCA_JPG

# 3. Machine Learning Algorithm Used

## Machine Learning Algorithm Used for Scoring
In this project, we used the Linear Regression algorithm from Python's scikit-learn library to score and predict outcomes.

## Why Did We Choose Linear Regression?
Linear regression is a machine learning technique used to predict a target variable (or response) based on one or more input variables (called explanatory variables). It works by finding a linear equation that best fits the relationship between the input variables and the target variable.

In this project, we used the LinearRegression class from the scikit-learn library, which is specifically designed for creating and using linear regression models. This algorithm was chosen because it is straightforward and effective for making predictions based on the data provided.

## What is Linear Regression?
Linear regression is a method that assumes a straight-line relationship between input variables (often called "x") and the output variable (called "y"). The goal is to find the best-fitting line that predicts y based on the values of x.

Simple Linear Regression: This is when we use just one input variable (x) to predict the output variable (y).
Multiple Linear Regression: When we have several input variables, we use a technique called multiple linear regression, which finds a way to predict y based on all the input variables combined.
The most common way to calculate the best-fitting line is called the Ordinary Least Squares method. This method minimizes the differences between the actual data points and the line we’re trying to fit, making the line as accurate as possible for the given data. This is why models created using this method are often referred to as Least Squares Regression models.

![PCA Process](Assests/Linear_Regression.png)
