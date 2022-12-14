# Fraud-Detection-Project

The aim of this project is to predict whether a credit card transaction is fraudulent. First of all, I analyzed the data well in order to draw my roadmap and choose the correct arguments I will use. Accordingly, I examined the frequency distributions of variables. I observed variable correlations and explored multicollinearity. I showed the distribution of the target variable's classes over other variables. Also, it is useful to take missing values and outliers.

After these procedures, I moved on to the model building stage by doing the basic data pre-processing.

I started with Logistic Regression and evaluated the model performance. I applied the SMOTE technique to increase the sample for unbalanced data. Next, I rebuilt the Logistic Regression model with SMOTE applied data and I observed its effect.

Then, I used three different algorithms in the model building phase. I have applied Logistic Regression, Random Forest and the Deep Learning Neural Network algorithm

In the final step, I deployed the model using Flask API.

# Tasks

#### 1. Exploratory Data Analysis & Data Cleaning

- Import Modules, Load Data & Data Review
- Exploratory Data Analysis
- Data Cleaning
   
#### 2. Data Preprocessing

- Scaling
- Train - Test Split

#### 3. Model Building

- Logistic Regression without SMOTE
- Apply SMOTE
- Logistic Regression with SMOTE
- Random Forest Classifier with SMOTE
- Neural Network

#### 4. Model Deployement

- Save and Export the Model as .pkl
- Save and Export Variables as .pkl 

# Determines
The datasets contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where it has **492 frauds** out of **284,807** transactions. The dataset is **highly unbalanced**, the positive class (frauds) account for 0.172% of all transactions.

**Feature Information:**

**Time**: This feature is contains the seconds elapsed between each transaction and the first transaction in the dataset. 

**Amount**:  This feature is the transaction Amount, can be used for example-dependant cost-senstive learning. 

**Class**: This feature is the target variable and it takes value 1 in case of fraud and 0 otherwise.


