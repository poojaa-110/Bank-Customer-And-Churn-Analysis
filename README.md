# 🏦 Bank Customer Retention & Churn Analysis

## 📌 Project Overview

This project is an **Excel-based Customer Retention and Churn Management Information System** designed to help a bank identify customer segments with higher churn risk and understand the characteristics associated with customer attrition.

This provides a structured view of customer churn using **PivotTables, KPI calculations, segmentation analysis, charts, and an executive dashboard**.

The primary business question addressed is:

> **Which customer segments are experiencing higher churn, and what customer characteristics should the bank monitor to improve customer retention?**

---

## 🎯 Business Objectives

The main objectives of this project are to:

- Monitor the overall customer churn rate.
- Track retained and churned customers.
- Identify customer segments with higher churn.
- Compare churn across geography, age, credit score, tenure, product usage, and customer activity.
- Identify high-risk customer segments requiring management attention.
- Provide actionable recommendations for customer retention.
- Present findings through an easy-to-understand MIS dashboard.
- Support management decision-making through data-driven insights.

---

## 🛠️ Tools & Techniques Used

### Microsoft Excel

The project was developed using Excel features including:

- Data cleaning
- Helper columns
- Excel formulas
- `IFS`
- `IFERROR`
- `COUNTIF`
- `COUNTIFS`
- PivotTables
- PivotCharts
- KPI calculations
- Conditional formatting
- Dashboard design
- Executive reporting

---

## 📊 Project Structure

The workbook is organized into the following sheets:

### 1. Raw_Data

Contains the original customer-level dataset.

This sheet is maintained as the source data layer and should not be directly modified during analysis.

---

### 2. Data cleaning and data preparation

Contains additional analytical classifications created from the raw customer attributes.

Key segmentation fields include:

- Age Group
- Credit Score Band
- Tenure Group
- Balance Band
- Salary Band
- Product Group
- Balance Missing indicator

These helper fields make it easier to perform consistent segment-level analysis using PivotTables.

---

### 3. Segment_Analysis

This sheet contains detailed customer segmentation analysis using PivotTables.

The analysis covers:

- Geography
- Gender
- Age Group
- Credit Score Band
- Tenure Group
- Balance Band
- Salary Band
- Product Group
- Credit Card ownership
- Active Membership

Key metrics include:

- Customer Count
- Churned Customers
- Churn Rate
- Retained Customers
- Retention Rate

---

### 4. Dashboard

The dashboard provides a management-level view of customer retention and churn.

#### Key KPIs

- Total Customers
- Churned Customers
- Churn Rate
- Retained Customers
- Retention Rate

#### Key Visualizations

- Churn Rate by Geography
- Churn Rate by Product Group
- Churn Rate by Credit Score Band
- Churn Rate by Age Group
- Churn Rate by Active Membership

The dashboard also includes a **Key Risk Segments** section to highlight customer groups requiring greater management attention.

---

### 5. Executive_Summary

The Executive Summary converts the analytical findings into management-oriented insights.

## 📈 Key KPIs

### Customer Churn Rate

Customer churn rate measures the percentage of customers who have exited the bank.

**Formula:**

```text
Churn Rate = Churned Customers / Total Customers
