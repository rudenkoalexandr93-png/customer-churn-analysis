# E-Commerce Customer Churn Analysis

## Project Overview

Customer churn is one of the most important business challenges for e-commerce companies. Acquiring a new customer is often more expensive than retaining an existing one.

The goal of this project is to analyze customer behavior, identify factors associated with churn, and provide actionable recommendations to improve customer retention.

---

## Business Problem

The company experiences customer churn, which negatively impacts revenue and customer lifetime value.

The objective of this analysis is to:

* Measure the overall churn rate
* Identify customer characteristics associated with churn
* Discover behavioral patterns linked to customer retention
* Provide data-driven business recommendations

---

## Dataset

The dataset contains **50,000 customer records** and **25 variables** describing customer demographics, engagement, purchase behavior, and churn status.

Target variable:

* **Churned**

  * 0 = Active Customer
  * 1 = Churned Customer

---

## Tools Used

* Python

  * Pandas
  * Matplotlib
  * Seaborn
* Jupyter Notebook
* Power BI
* GitHub

---

## Project Workflow

### 1. Data Understanding

* Loaded and explored the dataset
* Reviewed data structure and data types
* Assessed dataset dimensions

### 2. Data Quality Assessment

* Checked missing values
* Checked duplicate records
* Evaluated overall data quality

### 3. Exploratory Data Analysis (EDA)

Analyzed:

* Customer churn rate
* Age distribution
* Membership duration
* Login frequency
* Purchase activity
* Customer engagement metrics

### 4. Correlation Analysis

Identified variables most strongly associated with customer churn.

### 5. Report Development

Built an interactive Power BI Report to visualize churn metrics and key business insights.

---

## Key Findings

### Customer Churn Rate

* Total Customers: 50,000
* Churned Customers: 14,450
* Active Customers: 35,550
* Churn Rate: 28.9%

### Key Drivers of Churn

Customers with higher churn risk tend to:

* Contact customer support more frequently
* Abandon shopping carts more often
* Remain inactive for longer periods after their last purchase

### Customer Retention Indicators

Customers who stay active tend to:

* Log in more frequently
* Spend more time per session
* Use the mobile application more often
* Open marketing emails more frequently

---

## Business Recommendations

1. Identify customers who have not purchased within the last 30 days and target them with retention campaigns.

2. Monitor customers with high cart abandonment rates and provide personalized incentives.

3. Investigate causes of frequent customer service contacts and improve support processes.

4. Increase customer engagement through email marketing, loyalty programs, and mobile app initiatives.

5. Develop an early warning churn monitoring system based on engagement and purchase activity metrics.

---

## Power BI Report

Dashboard includes:

* KPI Cards

  * Total Customers
  * Churned Customers
  * Active Customers
  * Churn Rate %

* Customer Churn Distribution

* Login Frequency Analysis

* Days Since Last Purchase Analysis

* Customer Service Calls Analysis* Key Business Insights

---

## Report Preview

<img src="images/Report Preview.png" width="900">

---

## Project Structure

```text
customer-churn-analysis/
│
├── data/
├── ecommerce_customer_churn_dataset.csv   
└── customer_churn_clean.csv           
│
├── notebooks/
│   └── customer_churn_analysis.ipynb
│
├── dashboard/
│   └── Customer_Churn_Report.pbix
│
├── images/
│   └── Report Preview.png
│
└── README.md
```









