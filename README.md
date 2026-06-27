# Python | Statistical Analysis & A/B Testing

<p align="center">

![Python](https://img.shields.io/badge/Python-Programming-3776AB)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-D97706)
![SciPy](https://img.shields.io/badge/SciPy-Statistics-7C3AED)
![Status](https://img.shields.io/badge/Status-Completed-16A34A)

</p>

## 📋 Project Overview

**Objective:** Evaluate whether delivery performance impacts customer satisfaction using statistical analysis.

**Dataset:** E-Commerce Public Dataset by Olist (2016–2018)

**Analysis Type:** Exploratory Data Analysis (EDA), Correlation Analysis & A/B Hypothesis Testing

**Tools:** Python, Pandas, NumPy, SciPy, Plotly Express

---

## 📌 Executive Summary

This project analyzes Olist's e-commerce dataset to investigate the impact of delivery performance on customer satisfaction. Using Python, seven relational datasets were cleaned, merged, and analyzed through exploratory data analysis, descriptive statistics, and A/B hypothesis testing.

The findings revealed a statistically significant relationship between delivery delays and lower customer review scores (**p-value < 0.001**), providing data-driven recommendations to improve logistics performance and customer experience. Future work includes interactive dashboard development and deeper analysis of delivery trends.

---

## 🎯 Business Problem
Delivery performance is a critical operational metric that directly influences customer satisfaction in e-commerce. This project applies statistical analysis to determine whether late deliveries have a significant impact on customer review scores.

**Business Question:**

Do late deliveries lead to lower customer review scores than on-time deliveries?

---

## 📂 Dataset

The analysis uses the Brazilian E-Commerce Public Dataset by Olist, containing e-commerce transactions from **2016–2018**.

The project integrates **seven relational tables** covering customers, orders, products, sellers, payments, order items, and reviews. Together, the dataset contains **over 100,000 customer orders**, providing a complete view of the purchasing process from checkout to post-purchase customer feedback.

| Dataset | Description | 
|:---|:---|
| Orders | Order status, purchase and delivery dates | 
| Customers | Customer information | 
| Order Items | Products purchased and prices | 
| Products | Product details and categories |
| Sellers | Seller information |
| Payments | Payment methods and transaction values | 
| Reviews | Customer review scores and feedback| 

---

## 🛠️ Methodology

The analysis followed a structured data analytics workflow:

• Imported, explored, and validated seven relational datasets using Pandas.

• Cleaned the data by handling missing values, validating data types and checking duplicates.

• Engineered new analytical features including delivery time and delivery status.

• Integrated all datasets into a unified analytical table using primary and foreign keys.

• Performed descriptive statistical analysis and exploratory visualizations.

• Evaluated relationships between variables using correlation analysis.

• Conducted an Independent Two-Sample T-Test to determine whether delivery delays significantly affect customer satisfaction.

---

## 📊 Exploratory Data Analysis

Exploratory Data Analysis (EDA) was conducted to identify patterns, trends, and relationships within the data prior to statistical testing. The analysis focused on:

- Order value and delivery time distributions.
- Customer satisfaction trends.
- Product category and payment method distributions.
- Descriptive statistics for key business metrics.
- Correlation analysis between operational and customer experience variables.

<p align="center">
  <img
    src="https://github.com/user-attachments/assets/6a9dd3fd-8ca4-4114-9407-6edf39ca05b8"
    alt="Correlation Heatmap"
    width="900">
</p>

**Correlation Analysis**

The correlation matrix identified a moderate negative relationship (**-0.30**) between delivery time and customer review scores, indicating that longer delivery times are associated with lower customer satisfaction.

---

## 🧪 Statistical Analysis (A/B Testing)

An Independent Two-Sample T-Test was conducted to determine whether delivery delays significantly affect customer satisfaction.

The analysis compared two groups:

- Control Group: Orders delivered on or before the estimated delivery date.
- Treatment Group: Orders delivered after the estimated delivery date.

The null hypothesis assumed no difference in average review scores between the two groups, while the alternative hypothesis proposed that late deliveries result in lower customer satisfaction.

The statistical significance of the results was evaluated using a 95% confidence level (α = 0.05).

<p align="center">
  <img
    src="https://github.com/user-attachments/assets/3f8101d2-1617-4f65-856b-cbbb6bdc5d9c"
    alt="A/B Test Boxplot"
    width="900">
</p>

**A/B Test Findings**

The boxplot illustrates a clear separation between both groups, with customers receiving on-time deliveries consistently providing higher review scores than those experiencing delayed deliveries.

---

## 📈 Results

**Key Results**

| Metric | Result |
|:---|:---|
| Average Order Price | 140.55 | 
| Median Order Price | 92.01 | 
| Average Delivery Time | 11.98 days | 
| Average Review Score | 4.03 / 5 | 
| Correlation (Delivery Time vs Review Score) | -0.30 | 
| T-statistic | 156.66 | 
| P-value | <0.001 | 

**Key Finding**

- Customers receiving on-time deliveries reported an average review score of **4.29**, compared with **2.35** for late deliveries.
- Delivery time showed the strongest relationship with customer satisfaction among the variables analyzed.
- Most customer reviews were positive, with a median score of **5**.
- The Independent Two-Sample T-Test confirmed that delivery delays have a statistically significant impact on customer satisfaction (**p-value < 0.001**).

---

## 💼 Business Recommendations

- Improve delivery reliability to increase customer satisfaction.
- Monitor late deliveries through operational dashboards.
- Identify logistics partners and regions with poor delivery performance.
- Develop predictive models to detect orders at risk of delayed delivery.

---

## ⚙️ Tools & Skills

**Programming & Libraries**

- Python
- Pandas
- NumPy
- SciPy
- Plotly Express

**Data Analysis**

- Data Cleaning
- Data Wrangling
- Data Merging
- Feature Engineering

**Analytical Techniques**

- Exploratory Data Analysis (EDA)
- Descriptive Statistics
- Correlation Analysis
- A/B Testing
- Hypothesis Testing

**Business Skills**

- Business Insight Generation
- Data Storytelling
- Business Recommendations

---

## 🚀 Future Improvements

Future work could include:

- Developing an interactive dashboard to monitor delivery performance and customer satisfaction.
- Performing deeper analysis of delivery trends across different product categories, sellers, and time periods.
  
