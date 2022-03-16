# Telecom Churn Prediction Case Study
> In the telecommunication industry, customers tend to change operators if not provided with attractive schemes and offers. It is very important for any telecom operator to prevent the present customers from churning to other operators. In this case study would be to build an ML model which can predict if the customer will churn or not in a particular month based on the past data


## Table of Contents
* [Business Overview](#Business-Objective)
* [Technologies Used](#technologies-used)
* [Exploratory Data Analysis](#Steps)
* [Conclusions](#conclusions)

## Business-Objective

- To reduce customer churn, telecom companies need to predict which customers are at high risk of churn. The given dataset contains customer-level informations for few consecutive months June, July & August they are encoded as 6,7 & 8. The business objective is to predict the cusotmer which will churn in next month by analyzing the dataset High Value Customers:
- One of the primary goal is to identify high value customers which are more likely to churn, as most of the profit comes from high value customers. Customers which are likely to churn will starting decreasing rhe recharge amount and other facilities. To identify high value customers, total_rech_data can be calculated and total dataser can be filtered which are greater than 70th percentil of the data

> #dataset : loan.csv

## Technologies Used
- pandas - Version : 1.2.4
- numpy - Version : 1.20.1
- seaborn - Version : 0.11.1
- matplotlib - Version : 3.3.4
- statsmodels - Version : 0.12.2
- pandasql - Version : 0.7.3
- sklearn - Version :0.24.2

# Exploratory Data Analysis

## Steps

> EDA
- Data Clearning and Missing Data Analysis
- Outlier Analysis & Treatment Assumption values > Q3+1.5IQR and values < Q1-1.5IQR will be treated
- Transforming Categorical Columns
- Univariate Analysis
- Bivariate Analysis
- Multivariate Analysis
- Model Preperation
- Training and Test data split
- Feature Scaling - StandardScaler
- Strategy steps
- Handle Imbalance dataset using SMOTE
- PCA - Dimensionality Reduction
> Case1 :
- - Split train data into train and test split
- - Created below models using Hyper Parameter Tuning
- - LOGISTICREGRESSION
- - RANDOMFOREST
- - ADABOOST
- - XGBBOOST
- ## Made predictions by using combination of Random Forest + Adaboost + XGBOOST
> Case2 :
- - Use entire train dataset for model building using K Cross Validation
- - Created below models on entire train set
- - RANDOMFOREST
- - ADABOOST
- - XGBBOOST
- Made predictions by using combination of Random Forest + Adaboost + XGBOOST
- Model Evaluation & Assessment
- Prediction
- Made predictions on combination of case1 and case2
- Important Features
- Conclusion & Analysis

## Conclusions
- Telecom company should provide good offers to the customers who are using services from a roaming zone.
- Telecom company should provide some kind of STD and ISD packages to reduce churn rate.



## Contact
Created by [@shashank1989] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
