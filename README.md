# Customers Churn & Retention Predictive Analytics
## Project Overview

Customer retention is a critical aspect of customer relationship management, as acquiring new customers is often more costly than retaining existing ones. The objective of this project is to analyze customer data from a telecommunications company to identify customers at risk of leaving. By developing predictive models, we can suggest strategies to retain these customers through targeted incentives.

## Dataset

The dataset consists of two .rda files:

- Model_Building_Data: Used to train and validate predictive models. It contains information on both current and former customers.

- Implementation_Data: Used for business analysis and recommendations, containing information on 500 current customers.

## Features

The dataset includes the following variables:

- "Status": Indicates if the customer is active or has left.

- "SeniorCitizen": Binary indicator for senior citizen status.

- "Partner", "Dependents": Indicates if the customer has a partner or dependents.

- "Tenure": Duration of customer relationship in months.

- "PhoneService", "MultipleLines", "InternetService", "OnlineSecurity", "DeviceProtection",  "StreamingMovies": Information on customer services.

- "Contract": Contract type (Month-to-month, One year, Two year).

- "PaperlessBilling": Indicates if the customer uses paperless billing.

- "PaymentMethod": Payment method used by the customer.

- "MonthlyCharges", "TotalCharges": Billing amounts.

- "Gender": Customer's gender.

## Project Workflow

1. Data Preparation & Exploratory Data Analysis (EDA)

- Data cleaning and handling missing values.

- Exploratory analysis and visualizations.

- Relationship analysis between Status and independent variables.

- Feature engineering and dataset splitting (80% training, 20% testing).

2. Logistic Regression Model

- Build a logistic regression model to predict customer churn.

- Optimize the model based on AUC for ROC plots.

- Interpret coefficients and determine the best threshold for prediction accuracy.

3. Naive Bayes Model

- Train a Naive Bayes model and optimize it for AUC.

- Identify the best threshold for prediction accuracy.

4. Linear Discriminant Analysis (LDA)

- Develop an LDA model and optimize it for AUC.

- Identify the best threshold for prediction accuracy.

5. Quadratic Discriminant Analysis (QDA)

- Train a QDA model and optimize it for AUC.

- Identify the best threshold for prediction accuracy.

6. Decision Tree Model

- Build a decision tree model for customer churn prediction.

- Optimize for the highest prediction accuracy.

7. Model Comparison

- Compare all predictive models (excluding decision trees initially).

- Determine the best-performing model based on ROC plots.

- Assess decision tree performance separately.

8. Business Analysis & Recommendations

- Using the Implementation_Data file:

- Rank predictor importance.

- Estimate the number of customers likely to leave.

- Calculate potential revenue loss if no action is taken.

- Identify key factors influencing churn.

- Propose an incentive scheme to retain customers.

- Perform cost-benefit analysis to justify recommendations.

# Contributors: Huy Nguyen
