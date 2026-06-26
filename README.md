# nuteshsairam_2511693_part3_regression_insights

# Retail Store Sales Regression Analysis

## Project Overview

This project analyzes the factors that influence monthly sales across multiple retail stores using regression analysis. The objective is to identify the key business drivers of sales and provide data-driven recommendations that can help management improve store performance and make better strategic decisions.

---

# Business Problem

A retail company operates stores across different regions and store types. Management has observed that monthly sales vary significantly between stores and wants to understand which operational and business factors contribute most to these differences.

The goal of this analysis is to identify the variables that have the strongest relationship with monthly sales and build regression models that explain sales performance.

---

# Business Objective

The primary objective of this project is to determine the factors that significantly influence monthly sales using statistical regression techniques.

The analysis aims to:

* Identify the strongest predictors of monthly sales.
* Compare simple and multiple regression models.
* Evaluate model performance using statistical metrics.
* Provide business recommendations based on analytical findings.

---

# Dataset Description

The dataset contains monthly performance information for retail stores, including operational, marketing, customer, and environmental variables.

The dataset includes information such as:

* Store ID
* Month
* Region
* Store Type
* Marketing Spend
* Footfall
* Average Discount Percentage
* Staff Count
* Inventory Availability
* Competitor Distance
* Holiday Flag
* Customer Rating
* Monthly Sales
* Monthly Profit

---

# Variable Identification

## Dependent Variable

**monthly_sales**

Monthly sales represent the target variable that the regression models aim to predict and explain.

---

## Independent Variables

The following variables are considered potential predictors of monthly sales:

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

---

# Variable Classification

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

Store ID is a unique identifier used to distinguish individual stores. Since it does not represent a business characteristic, it is excluded from regression analysis.

## monthly_profit

Monthly profit is another business outcome rather than a predictor of sales. Since the objective of this project is to explain monthly sales, monthly profit is not included as an independent variable.

---

# Data Preparation Plan

Before building regression models, the dataset will be prepared by:

* Checking for missing values.
* Identifying duplicate records.
* Verifying data types.
* Creating dummy variables for categorical features such as Region and Store Type.
* Ensuring variables are suitable for regression analysis.

---

# Regression Strategy

The analysis will be performed in multiple stages:

1. Exploratory Data Analysis (EDA)
2. Data Cleaning and Preparation
3. Dummy Variable Creation
4. Simple Linear Regression
5. Multiple Linear Regression
6. Model Comparison
7. Residual Analysis
8. Business Interpretation
9. Final Recommendations

---

# Expected Business Outcomes

The analysis is expected to identify the operational and marketing factors that have the greatest influence on monthly sales.

The findings can help management:

* Improve marketing investment decisions.
* Optimize staffing levels.
* Increase inventory availability.
* Improve customer satisfaction.
* Enhance overall store performance.

---

# Tools Used

* Microsoft Excel
* Excel Data Analysis ToolPak
* Linear Regression
* Multiple Linear Regression
* Statistical Analysis

This README will be updated as each stage of the project is completed.
