# Customer Intermittent Demand Prediction (Northwind Case Study)

# Summary
This project builds a machine learning model to predict whether a customer 
will place an order in the next month using transactional data from the 
Northwind dataset.

The problem represents an intermittent demand scenario, where purchases 
are irregular and sparse across time.

This type of prediction can support:
- Targeted marketing campaigns
- Sales prioritization
- Customer retention strategies

## Business Problem

In B2B environments, customers often purchase irregularly.
Predicting which customers are likely to buy next month allows:

- Better sales planning
- Focused outreach
- Improved inventory management

## Modeling

The problem was framed as binary classification:
Target = 1 if customer purchases next month, else 0.

Models tested:
- Logistic Regression
- Random Forest
- XGBoost
- Deep Learning

Evaluation strategy:
- Time-based split (train on past, test on future)
