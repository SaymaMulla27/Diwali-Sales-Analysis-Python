# 🪔 Diwali Sales Analysis using Python

## 📊 Project Overview

This project explores consumer behavior during the Diwali festival using a real-world retail sales dataset. The goal is to identify trends, analyze spending patterns, and provide actionable business insights to improve marketing strategies and product placement for future festive seasons.

> 🔍 Insight Highlight: Married women aged 26–35, particularly from UP, Maharashtra, and Karnataka, working in IT, Healthcare, and Aviation, are the biggest contributors to Diwali sales!

---

## 📁 Dataset

- **Source:** Diwali Sales Data.csv
- **Size:** 11,251 records | 13 columns
- **Features:**
  - Demographics (Age, Gender, Marital Status, State, Occupation)
  - Product data (Product ID, Category)
  - Transactional data (Order count, Purchase Amount)

---

## 🔧 Tools & Technologies

- **Language:** Python
- **Libraries:** Numpy, Pandas, Matplotlib, Seaborn
- **IDE:** Jupyter Notebook

---

## 🧹 Data Cleaning

- Removed irrelevant columns (`Status`, `unnamed1`)
- Handled null values in `Amount` column
- Converted data types (`Amount` to `int`)
- Renamed column: `Marital_Status` ➝ `Married` (for clarity)

---

## 📈 Exploratory Data Analysis (EDA)

The analysis answers several business questions with the help of visualizations:

### 1. 🧍 Gender-Based Analysis
- Female users not only shop more but also spend more.

### 2. 📅 Age Group vs Spending
- 26–35 age group is the most active, especially females.

### 3. 📍 State-Wise Performance
- Highest orders and revenue from **UP**, **Maharashtra**, and **Karnataka**.

### 4. 💍 Marital Status & Spending
- Married women dominate the sales — festive spirit in full swing! 🛍️

### 5. 💼 Occupation Analysis
- Top professions: **IT**, **Healthcare**, and **Aviation** contribute the most to revenue.

### 6. 🛒 Product Category Performance
- Bestsellers: **Food**, **Clothing**, and **Electronics**.
- Also included: Top 10 most sold products by Product ID.

---

## 📌 Key Business Insights

| Feature           | Insight                                                                 |
|------------------|-------------------------------------------------------------------------|
| Gender           | Women purchase more and spend more during Diwali                        |
| Age Group        | 26–35 is the prime shopping age group                                   |
| Marital Status   | Married individuals (esp. women) shop significantly more                |
| Location         | North & West India dominate sales                                        |
| Occupation       | White-collar sectors like IT & Healthcare are major spenders            |
| Products         | Food, clothing, electronics are top-selling categories                  |

---
