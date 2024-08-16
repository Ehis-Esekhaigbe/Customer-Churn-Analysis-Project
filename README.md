
# Customer Churn Analysis Project
## Table of Contents
1. [Project Overview](#project-overview)
2. [Data Sources](#data-sources)
3. [Tools](#tools)
4. [Data Cleaning/Preparation](#data-cleaningpreparation)
5. [Exploratory Data Analysis](#exploratory-data-analysis)
6. [Data Analysis](#data-analysis)
7. [Results](#results)
8. [Recommendations](#recommendations)
9. [Limitations](#limitations)
    
## Project Overview
This project aims to analyze customer churn for a telecommunications company. The goal is to identify key factors contributing to customer churn and provide actionable insights to reduce churn rates.

## Data Sources
1. **Customer Data**: [CSV file containing customer demographics, account information, and services subscribed to](link_to_data).
2. **Churn Data**: [CSV file containing information on whether a customer has churned](link_to_data).

## Tools
1. **Python**: The primary programming language used for analysis.
2. **Pandas**: For data manipulation and analysis.
3. **NumPy**: For numerical computations.
4. **Matplotlib & Seaborn**: For data visualization.
5. **Scikit-learn**: For building predictive models.
6. **Jupyter Notebook**: For interactive data exploration and documentation.

## Data Cleaning/Preparation
1. **Handling Missing Values**: Identified and imputed missing values using mean/mode imputation.
2. **Feature Encoding**: Converted categorical variables into numerical values using one-hot encoding.
3. **Data Normalization**: Scaled numerical features to ensure all features are on the same scale.
   
## Exploratory Data Analysis
1. **Demographic Analysis**: Examined the distribution of customer demographics such as age, gender, and income.
2. **Service Usage Analysis**: Analyzed customer service usage patterns and their correlation with churn.
3. **Churn Rate Analysis**: Calculated and visualized the overall churn rate and churn rate across different customer segments.
   
## Data Analysis
**Correlation Analysis**: Identified correlations between customer features and churn.
**Predictive Modeling**: Built a logistic regression model to predict customer churn based on the identified features.
**Model Evaluation**: Evaluated the model using accuracy, precision, recall, and AUC-ROC metrics.

## Results
1. The model achieved an accuracy of 85%, with a precision of 80% and a recall of 75%.
2. The most significant factors contributing to churn were customer tenure, contract type, and monthly charges.
   
## Recommendations
1. **Customer Retention Programs**: Implement targeted retention programs for customers with high monthly charges and shorter tenure.
2. **Contract Enhancements**: Promote longer-term contracts with added benefits to reduce churn.
3. **Service Optimization**: Optimize services that are underutilized to increase customer satisfaction and reduce churn.
   
## Limitations
1. **Data Limitation**: The analysis is based on historical data, and the results may not fully capture future churn patterns.
2. **Model Generalization**: The model may not generalize well to other telecommunications companies without further tuning and validation.
3. **Feature Selection**: Some potentially influential features may have been overlooked due to the initial scope of the project.
