# 📊 Customer Behavior Analysis

An end-to-end **Data Analytics & Business Intelligence project** that analyzes customer shopping behavior to extract meaningful business insights using **Python, MySQL, and Power BI**.

---

## 📌 Project Overview

The **Customer Behavior** project focuses on understanding how customers interact with products, discounts, payment methods, and demographics.  
The goal is to help businesses improve **customer targeting, sales strategy, and decision-making** using data-driven insights.

This project demonstrates a **complete data pipeline**:
> Raw CSV → Data Cleaning & Feature Engineering → Database Storage → Interactive Dashboard

---

## 🎯 Objectives

- Analyze customer purchasing patterns  
- Understand the impact of gender, age, and location on revenue  
- Study the effect of discounts and promo codes  
- Identify popular product categories, sizes, and payment methods  
- Build an interactive dashboard for business users  

---

## 🧰 Tools & Technologies Used

- **Python** (Pandas, NumPy)
- **PyCharm** (Data Analysis & Development)
- **MySQL** (Database & SQL Queries)
- **SQLAlchemy** (Python–MySQL Integration)
- **Power BI** (Interactive Dashboard & Visualization)
- **GitHub** (Version Control & Project Hosting)

---

## 📂 Dataset Information

- **File Name:** `customer_shopping_behavior.csv`
- **Total Records:** 3900
- **Total Columns:** 18

### Key Attributes:
- Customer demographics: `age`, `gender`, `location`
- Purchase details: `item_purchased`, `category`, `purchase_amount`, `season`
- Behavior metrics: `review_rating`, `previous_purchases`
- Payment & offers: `payment_method`, `discount_applied`, `promo_code_used`

---

## 🧹 Data Preprocessing (Python)

Performed using **Pandas** in PyCharm:

- Loaded CSV dataset
- Checked data types and null values
- Filled missing `review_rating` using **category-wise median**
- Standardized column names
- Created new features:
  - `age_group` (Young Adult, Adult, Middle-Age, Senior)
  - `purchase_frequency_days`
- Cleaned and prepared data for database insertion

---

## 🗄️ Database Integration (MySQL)

- Created MySQL database: `customer_behavior`
- Exported cleaned data using **SQLAlchemy**
- Performed SQL queries for:
  - Gender-wise revenue analysis
  - Category-level insights
  - Purchase behavior validation

---

## 📊 Power BI Dashboard

An interactive dashboard was created to visualize:

- 💰 Total Revenue
- 👥 Customer Count
- 👨‍👩‍👧 Gender-wise Purchase Analysis
- 🌍 Location-wise Customer Distribution
- 🎨 Color & Size Preferences
- 💳 Payment Method Usage
- ⭐ Review Rating Trends

> The dashboard allows dynamic filtering by **Gender** and **Payment Method**.

---

## 🔍 Key Insights

- Male customers contributed higher total revenue
- Clothing category dominated overall purchases
- Medium (M) size products were most popular
- Credit Card and PayPal were the most used payment methods
- Discounts and promo codes significantly increased purchase frequency

---

