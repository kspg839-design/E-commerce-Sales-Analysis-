# 📂 Dataset Description – Online Retail Data

## 📌 Overview

This dataset contains all transactions occurring between **01 December 2010 and 09 December 2011** for a **UK-based, non-store online retail company**.

The company mainly sells **unique all-occasion gifts**, and a significant portion of its customers are **wholesalers**.

---

## 📊 Dataset Characteristics

* **Type:** Multivariate, Sequential, Time-Series
* **Domain:** Business / E-commerce
* **Total Records:** 541,909 transactions
* **Total Features:** 8

---

## 🎯 Analytical Applications

This dataset can be used for:

* Customer Segmentation (RFM Analysis)
* Sales Trend Analysis
* Clustering
* Classification
* Customer Behavior Analysis

---

## 📑 Feature Information

| Variable Name | Role    | Type        | Description                                                                       |
| ------------- | ------- | ----------- | --------------------------------------------------------------------------------- |
| InvoiceNo     | ID      | Categorical | Unique 6-digit transaction ID. If it starts with 'C', it indicates a cancellation |
| StockCode     | ID      | Categorical | Unique 5-digit product code                                                       |
| Description   | Feature | Categorical | Product name                                                                      |
| Quantity      | Feature | Integer     | Number of items purchased per transaction                                         |
| InvoiceDate   | Feature | Date-Time   | Date and time of transaction                                                      |
| UnitPrice     | Feature | Continuous  | Price per unit (in GBP £)                                                         |
| CustomerID    | Feature | Categorical | Unique customer identifier                                                        |
| Country       | Feature | Categorical | Customer's country                                                                |

---

## ⚠️ Data Notes

* Transactions with **InvoiceNo starting with 'C'** indicate cancellations
* Dataset primarily represents **UK-based transactions**
* Prices are recorded in **Pound Sterling (£)**
* No explicit missing values are reported, but preprocessing may still be required

---

## 📚 Source

* Dataset: **UCI Machine Learning Repository**
* Link: https://archive.ics.uci.edu/dataset/352/online+retail
* Paper: *Data Mining for the Online Retail Industry: A Case Study of RFM Model-Based Customer Segmentation Using Data Mining*
* Authors: Daqing Chen, Sai Liang Sain, Kun Guo (2012)
* Published in: Journal of Database Marketing and Customer Strategy Management

---

## 💡 Usage in This Project

In this project, the dataset is used to:

* Analyze revenue trends 📈
* Identify top-performing products 🏆
* Perform customer segmentation 🧑‍🤝‍🧑
* Detect business risks using Pareto analysis ⚠️

---
