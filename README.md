# nuteshsairam_2511693_part3_regression_insights

# Retail Store Sales Regression Insights

## Project Overview

This project analyzes the factors that influence monthly sales across retail stores using regression analysis in Microsoft Excel. The objective is to identify the business variables associated with monthly sales, compare regression models, and provide data-driven recommendations for improving store performance.

---

# Business Problem

The retail company operates multiple stores across different regions and store formats. Management has observed variation in monthly sales across stores and wants to understand which operational, marketing, and customer-related factors are associated with higher sales.

The analysis aims to answer the following business question:

**Which business factors have the greatest influence on monthly sales, and how can management use these insights to improve store performance?**

---

# Business Objective

The objectives of this project are to:

* Identify the key drivers of monthly sales.
* Build and compare simple and multiple regression models.
* Evaluate model performance using regression statistics.
* Interpret model outputs in business terms.
* Recommend actions based on analytical findings.

---

# Dataset Information

**Dataset Name:** `business_regression_data.xlsx`

**Worksheet Used:** `store_performance`

**Records:** 320 store observations

**Variables:** 14 columns

---

# Variables in the Dataset

| Variable                   | Description                           |
| -------------------------- | ------------------------------------- |
| store_id                   | Unique identifier for each store      |
| month                      | Reporting month                       |
| region                     | Store region                          |
| store_type                 | Type of retail store                  |
| marketing_spend            | Monthly marketing expenditure         |
| footfall                   | Number of customer visits             |
| avg_discount_pct           | Average discount percentage           |
| staff_count                | Number of employees                   |
| inventory_availability_pct | Inventory availability percentage     |
| competitor_distance_km     | Distance to nearest competitor        |
| holiday_flag               | Holiday indicator (0 = No, 1 = Yes)   |
| customer_rating            | Average customer rating               |
| monthly_sales              | Monthly sales value (Target Variable) |
| monthly_profit             | Monthly profit                        |

---

# Variable Classification

## Dependent Variable

* monthly_sales

## Independent Variables

* marketing_spend
* footfall
* avg_discount_pct
* staff_count
* inventory_availability_pct
* competitor_distance_km
* holiday_flag
* customer_rating
* region
* store_type

## Numerical Variables

* marketing_spend
* footfall
* avg_discount_pct
* staff_count
* inventory_availability_pct
* competitor_distance_km
* customer_rating
* monthly_sales
* monthly_profit

## Categorical Variables

* region
* store_type

## Binary Variable

* holiday_flag

---

# Variables Excluded from Regression

## store_id

Excluded because it is a unique identifier and does not provide predictive information about sales.

## monthly_profit

Monthly profit is treated as a separate business outcome. Since the objective of this project is to explain monthly sales, it is not used as an independent variable.

---

# Data Preparation Plan

The following preprocessing steps will be completed before regression analysis:

* Review the dataset for missing values.
* Check for duplicate records.
* Verify data types.
* Create dummy variables for categorical variables (`region` and `store_type`).
* Prepare the dataset for regression modelling.

---

# Regression Approach

The project will be completed in the following stages:

1. Data Understanding
2. Data Preparation
3. Dummy Variable Creation
4. Simple Linear Regression
5. Multiple Linear Regression
6. Model Comparison
7. Residual Analysis
8. Business Interpretation
9. Final Recommendation

---

# Tools Used

* Microsoft Excel
* Excel Data Analysis ToolPak
* Linear Regression
* Multiple Linear Regression

---

ession models, and business insights are completed during the project.
