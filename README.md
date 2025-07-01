# 📊  Churn Analysis Dashboard

## 📁 Project Overview

This project presents an interactive *Power BI dashboard* for analyzing customer churn in a telecommunications company. The dashboard provides insights into churn reasons, customer demographics, subscription types, and account behaviors, helping stakeholders make data-driven decisions to reduce churn.

## 🧾 Dataset Summary

The dataset consists of *4891 total customers, The data includes:
- Contract type
- Churn reason
- International plan usage
- Total charges
- Customer demographics (gender, age)
- Account length

## 📊 Dashboard Features

The dashboard is broken down into the following sections:

- 🔢 *Top KPIs*:  
  - Total Customers: 4,891
  - Intl Chargers: 169k
  - Monthly charges:141k
  - Total Charges: 6M

- 📌 *Visuals*:  
  - *Churn Customers by gender 
  - *Churn Reason Breakdown*  
  - *Payment method by groups 
  - customers in group by contract type
  - *Churn charges

- 📂 *Filters*:  
  - customers slicer 
     

## 🧠 Insights & Highlights

- *Competitor-related churn is highest*, followed by dissatisfaction and attitude issues.
- Majority of churned customers are on *month-to-month contracts*.
- Churn is more common among customers with *shorter account lengths*.
- Customers using *unlimited data* show higher churn behavior.

## 📐 DAX Measures Used


-- Total Customers
Total Customers = COUNTROWS(Customers)

-- Total Charges
Total Charges = SUM(Customers[TotalCharges])

