# 📊 Fintech Transaction Analysis & Fraud Detection

## 🔍 Project Overview

This project focuses on analyzing a fintech transaction dataset to uncover insights related to **transaction behavior, fraud detection, and revenue generation**. The dataset was cleaned, transformed, and analyzed using **Excel, SQL, and Power BI**.

---

## 🎯 Objectives

* Clean and preprocess raw transaction data
* Identify and handle missing and inconsistent values
* Analyze transaction patterns across customers, regions, and payment methods
* Detect fraudulent transactions and calculate fraud rate
* Derive business insights for risk management and decision-making

---

## 🧹 Data Cleaning Steps

* Standardized `Transaction_Status` (SUCCESS / FAILED / UNKNOWN)
* Handled missing values in `Payment_Method`, `Region`, and other categorical fields
* Replaced blanks with **"Unknown" / "Not Specified" / 0 / 1** where appropriate
* Converted data types (dates, numeric values)
* Identified duplicate `Transaction_IDs` and flagged them
* Created derived columns:

  * `Normalized_Amount` (currency conversion using Conversion_Rate)
  * `Revenue` (Processing_Fee)
  * `Fee_Percentage`

---

## 📊 Analysis Performed

### 1. Transaction Analysis

* Total transaction amount by **Account_Type** and **Transaction_Type**
* Monthly transaction trends using `Transaction_Date`

### 2. Customer Insights

* Identified **Top 5 customers** based on total transaction value
* Customer-level transaction frequency analysis

### 3. Regional Analysis

* Average transaction amount per **Region**
* Regional contribution to overall transaction volume

### 4. Fraud Analysis

* Calculated **Fraud Rate (%)**
* Compared **successful vs failed transactions**
* Identified high-risk:

  * Payment methods
  * Regions
  * Transaction categories

### 5. Revenue Analysis

* Total **processing fee (revenue)** by Payment Method
* Profitability insights using fee percentage

---

## 🛠️ Tools & Technologies

* **Microsoft Excel** → Data cleaning, pivot tables, analysis
* **SQL** → Data querying and aggregation
* **Power BI** → Dashboard creation and visualization

---

## 📈 Key Insights

* Certain **payment methods** show higher fraud rates
* **High-value transactions** are more prone to fraud
* Specific **regions** contribute significantly to transaction volume
* Processing fees provide a steady **revenue stream** in fintech models

---

## 📊 Dashboard Features (Power BI)

* Fraud Rate KPI
* Transaction Trends (Monthly)
* Revenue by Payment Method
* Fraud Segmentation (Region, Payment Type)
* High-Value Transaction Analysis

<img width="1214" height="694" alt="image" src="https://github.com/user-attachments/assets/17445b6f-6603-4b5d-ac0b-53d0a9e3921f" />


---

## 🚀 Business Recommendations

* Implement stricter verification for high-value transactions
* Monitor high-risk regions and payment methods
* Use real-time fraud detection systems
* Improve data validation at the source

---

## 📁 Project Structure

```
├── data/
│   └── fintech_dataset.csv
├── excel/
│   └── cleaned_fintech_analysis.xlsx
├── sql/
│   └── queries.sql
├── powerbi/
│   └── dashboard.pbix
└── README.md
```

---

## 💡 Future Enhancements

* Build a **machine learning fraud detection model**
* Implement real-time streaming analytics
* Integrate external datasets for deeper insights

---

## 👤 Author

**Your Name**
MBA – Business Analytics

---

## ⭐ If you found this useful

Give this repository a ⭐ and feel free to connect!
