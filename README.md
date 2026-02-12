# 🛒 E-Commerce Consumer Behavior Analysis

## 📌 Overview

This project analyzes real-world online retail transaction data to understand customer purchasing behavior, identify valuable customers, and predict future purchase likelihood.

The goal is not just visualization — but **business decision support**:

* Who are the loyal customers?
* Who is about to churn?
* Which customers should receive marketing campaigns?

---

## 📊 Dataset

The dataset contains transactional logs of an online retail store.

Each row represents a **product purchase inside an order**, not a complete order.

Important columns:

* InvoiceNo → Order ID
* StockCode → Product ID
* Description → Product Name
* Quantity → Units purchased
* InvoiceDate → Purchase time
* UnitPrice → Price per unit
* CustomerID → Unique customer
* Country → Customer location

💡 One order can contain multiple products → therefore multiple rows.

---

## 🎯 Problem Statement

Businesses often run marketing campaigns blindly.
This leads to:

* money spent on inactive customers
* ignoring loyal customers
* low conversion rate

The objective was to:

1. Understand customer buying behavior
2. Segment customers based on value
3. Predict whether a customer will purchase again

---

## ⚙️ Steps Performed

### 1️⃣ Data Cleaning

* Removed cancelled orders (InvoiceNo starting with C)
* Removed negative quantity & invalid prices
* Handled missing Customer IDs
* Converted InvoiceDate to datetime format

### 2️⃣ Feature Engineering (RFM Analysis)

Created customer behavior metrics:

* Recency → Days since last purchase
* Frequency → Number of orders
* Monetary → Total money spent

This converts raw billing logs → customer intelligence.

### 3️⃣ Customer Segmentation

Customers categorized into:

* High Value Customers
* Regular Customers
* Low Value Customers
* At Risk Customers

### 4️⃣ Predictive Modeling

Logistic Regression used to predict:

> Will the customer purchase again?

---

## 🤖 Why Logistic Regression?

* Interpretable for business teams
* Works well for behavioral probability prediction
* Fast baseline model for churn prediction

---

## 📈 Model Evaluation

Model performance measured using Accuracy Score on test data.

---

## 🚧 Challenges Faced

* Billing dataset ≠ Order dataset
* One purchase spread across multiple rows
* Handling inconsistent date formats
* Converting transaction data into customer-level data

---

## 📚 Key Learnings

* Real data is messy and needs business understanding
* Feature engineering matters more than model complexity
* Analytics must answer business questions, not just graphs
* Data analyst work = translating logs → decisions

---

## 🧠 Business Impact

This system helps companies:

* Target the right customers
* Reduce marketing cost
* Prevent customer churn
* Increase retention

---

## 🛠️ Tech Stack

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

---

## 👩‍💻 Author

Bhavya Jain
