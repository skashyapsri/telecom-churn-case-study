# Telecom Churn Case Study

## Problem Statement

### Business Problem Overview

In the telecom industry, customers have the freedom to choose from multiple service providers and actively switch from one operator to another. This competitive market witnesses an average annual churn rate of 15-25%. It costs significantly more to acquire a new customer than to retain an existing one, making customer retention a paramount goal.

For many established telecom operators, retaining high-profit customers is the top business priority. To reduce customer churn, telecom companies need to predict which customers are at a high risk of churning. This project focuses on analyzing customer-level data from a leading telecom firm and building predictive models to identify high-risk churn customers.

### Understanding and Defining Churn

Churn, in the context of the telecom industry, can be defined in several ways:

**Revenue-based churn:** Customers who have not utilized any revenue-generating facilities, such as mobile internet, outgoing calls, SMS, etc., over a specified period.

**Usage-based churn:** Customers who have not made any usage, either incoming or outgoing, of calls, internet, etc., over a period.

This project adopts the **usage-based** definition of churn.

### High-value Churn

In the Indian and Southeast Asian market, around 80% of revenue comes from the top 20% of customers, known as high-value customers. Reducing churn among high-value customers is critical to minimizing revenue loss.

### Understanding the Business Objective and the Data

The dataset contains customer-level information for four consecutive months: June, July, August, and September. The goal is to predict churn in the ninth month using data from the first three months.

### Customer Behavior During Churn

Customer churn doesn't happen instantly; it occurs over time, with distinct phases:

1. **The 'good' phase:** Customers are satisfied and behave normally.

2. **The 'action' phase:** Customers start experiencing issues, such as better offers from competitors or service quality problems. Identifying high-churn-risk customers during this phase is crucial.

3. **The 'churn' phase:** Customers are considered to have churned.

### Data Preparation

Key data preparation steps include:

1. **Deriving new features:** Creating important features that can serve as indicators of churn.

2. **Filtering high-value customers:** Defining high-value customers and focusing on churn prediction for this segment.

3. **Tagging churners and removing attributes:** Identifying churned customers based on the fourth month and discarding related attributes.

### Modelling

The modelling phase aims to:

1. Predict whether a high-value customer will churn in the near future.
2. Identify significant predictor attributes for churn.

Key steps in the modelling phase include:

1. Preprocessing data, converting columns to appropriate formats and handling missing values.
2. Conducting exploratory analysis to extract useful insights.
3. Deriving new features.
4. Reducing the number of variables using PCA (Principal Component Analysis).
5. Training various models, tuning model hyperparameters, and handling class imbalance.
6. Evaluating models using appropriate metrics, with a focus on identifying churners.
7. Building another model to identify important predictor attributes that help understand indicators of churn.
8. Recommending strategies to manage customer churn based on observations.

This project aims to provide actionable insights for telecom companies to retain high-value customers, reduce churn, and ultimately improve business performance.