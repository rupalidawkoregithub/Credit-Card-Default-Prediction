#  **Credit-Card-Default-Prediction**

This project aimed at predicting the case of customers default payment in taiwan. data is of 29999 customers with 6 months transection history.


## **Evaluation Criteria:**

The evaluation criteria was based on Recall value , F1 Score and Accurance percentages. Higher the score better will be the prediction

## **Problem Statement**:

The main objective of this project - credit card default prediction is to develop a model that accurately predicts the likelihood of a credit card holder defaulting on their debt payment in the near future. The model should take into account various factors such as the cardholder's credit history and other relevant financial information. The goal is to minimize false negatives (predicting a non-default when the cardholder actually defaults) and false positives (predicting a default when the cardholder is able to repay their debt) while maximizing the overall accuracy of the prediction.

## **Approach:**

The project for credit card default prediction aims to develop a model that can accurately predict the likelihood of a credit card holder defaulting on their payments. **The project typically includes the following steps:**


**Data cleaning and preprocessing:** Removing missing or irrelevant data and transforming the data into a format suitable for analysis.

**Exploratory Data Analysis (EDA):** Analyzing the distribution of the data and identifying any patterns or trends that may be relevant to the prediction model.different types of graphs by separating them into univariate, bivariate and multivariate categories as a result, We came accross some meaningful insights that helped us to make future decisions of ML model pipeline

**Feature selection:** Choosing the most relevant variables to include in the prediction model based on the results of the EDA.Under the umbrella of feature engineering we have detected and treated the outliers with the help of IQR technique and capped all the outliers of continous features in 25-75 percentile. Also, we noticed that some of the features were categorical in nature and ML model can not understand the language of alphabets(strings).So, we have encoded them into numericals using One-Hot Encoding technique as they were unordered in nature.

**Model development:** Training and testing different machine learning algorithms, such as  random forests,XG Boot, and lightgbm to find the best model for predicting credit card default.

**Model evaluation:** Evaluating the performance of the selected model using metrics such as accuracy, recall, and F1 score.

 The successful implementation of this model can help credit card companies make informed decisions about the risk associated with lending to individual customers and can also aid customers in managing their credit card debt.
