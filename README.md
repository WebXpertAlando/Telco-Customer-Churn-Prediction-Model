# Week5_Capstone_Project_2024
## Data Engineering: Option 2:Telco Customer Churn Prediction and Retention Strategy 
### Introduction
Customer churn is the percentage of customers that stopped using your company's product or service during a certain time frame. It’s easier to keep an existing customer than to gain a new one, and it’s much simpler to save a departing customer than to tempt them back later. Customer churn is measured using customer churn rate. That’s the number of people who stopped being customers during a set period of time, such as a year, a month, or a financial quarter.
### About Dataset
Telco customer churn contains information about a fictitious telecom company providing home phone and Internet services to 7043 customers in California in the third quarter. It includes which customers left, stayed or signed up for service.

##  1. Data Collection:
Access the Telco customer churn dataset from Kaggle, which includes information on demographics, transaction history, customer service interactions, subscription details, and whether the customer churned.


##  2. Data Preprocessing.
Data preprocessing is the processes of cleaning, transforming, and integrating of data in order to make it ready for analysis. The goal of data preprocessing is to improve the quality of the data and to make it more suitable for the specific data mining task.

### Data Preprocessing Steps.

#### Handling Missing Values
From our Dataset of Churn it contained no missing values there by making our models fit correctly. There was also no issues of underfitting or overfittig since our standardization and feature engineering was well taken care of.

#### Encoding categorical variables
There are many ways to encode categorical variables for modeling, although the three most common are as follows:
- Integer Encoding: Where each unique label is mapped to an integer.
- One Hot Encoding: Where each label is mapped to a binary vector.
- Learned Embedding: Where a distributed representation of the categories is learned.
In this churn Customer prediction, we have features belonging to categical variables such as SeniorCitizen, TotalCharges, Churn, and Gender. 




## 3. Exploratory Data Analysis









