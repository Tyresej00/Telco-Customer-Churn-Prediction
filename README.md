# Customer Churn Prediction Project
## Project Overview
This project focuses on predicting the determining factors of customer churn for a telecommunications business. By identifying why and when clients leave, the business can proactively strategize retention campaigns to protect its customer base and boost revenue.

## Data Source & Preparation
I used the Telco Dataset containing 7043 rows and 21 variables. The data was inspected which revealed incorrect data types and missing values. I converted the "TotalCharges" column from and object to a numeric format. This column was also missing values, so I imputed these missing values with the median of the training set to prevent data leakage. I removed the unique identifier column "customerID" as this would cause the model to run ineffectively.
Furthermore I encoded and scaled the data. I then completed the test/train split and separated the target variable, "Churn".

##Exploratory Data Analysis
I aimed to better understand the data prior to model generation. 
