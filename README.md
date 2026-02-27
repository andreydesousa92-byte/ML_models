# Customer Intermittent Demand Prediction (Northwind Case Study)

This project implements a machine learning model to predict whether a customer will place an order in the next month, using transactional data from the Northwind dataset.  
The notebook is designed to run on **Google Colab**, simplifying environment setup and dependency management.  

---

## Project Summary

In B2B environments, customer purchases are often **intermittent**, meaning they occur irregularly and sparsely over time.  
This project aims to predict future purchases at the **customer level**, which can support:

- Targeted marketing campaigns  
- Prioritization of sales efforts  
- Improved customer retention strategies  

The dataset used is the classic **Northwind dataset**, which contains historical transactional data across multiple customers.

---

## Business Problem

Predicting which customers are likely to make a purchase next month enables companies to:

- Plan sales more effectively  
- Focus outreach on high-probability customers  
- Optimize inventory and supply chain decisions  

By anticipating customer demand, businesses can reduce missed opportunities and better allocate resources.

---

## Modeling Approach

The problem is formulated as a **binary classification task**:

- **Target = 1** if the customer places an order next month  
- **Target = 0** otherwise  

### Models Tested

- Logistic Regression  
- Random Forest  
- XGBoost  
- Deep Learning (Neural Networks)  

### Evaluation Strategy

- **Time-based split:** Training on historical data and testing on future periods  
- Focus on realistic performance estimation for **future demand prediction**  

---

## Notes

- All preprocessing and modeling is implemented in a single notebook for simplicity.  
- Data is stored in the `data/raw` folder and loaded via relative paths.  
- The project assumes execution in **Google Colab**, which already provides the necessary Python environment and libraries.  
