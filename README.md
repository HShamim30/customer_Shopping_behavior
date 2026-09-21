# 🛍️ Customer Shopping Behavior Analysis

An end-to-end data analytics project that analyzes customer shopping behavior using **Python, PostgreSQL/SQL, and Power BI**.

The project focuses on understanding customer purchasing patterns, product preferences, discounts, subscriptions, shipping preferences, customer loyalty, and demographic trends to generate meaningful business insights.

---

## 📌 Project Overview

Retail businesses generate large amounts of customer transaction data, but raw data alone does not provide actionable insights.

This project analyzes **3,900 customer purchase records** to understand:

- Customer spending patterns
- Product and category preferences
- Discount usage
- Customer loyalty and repeat purchases
- Subscription behavior
- Shipping preferences
- Customer demographics
- Product ratings
- Revenue contribution across age groups

The overall business objective is to identify trends that can help improve **customer engagement, sales, loyalty, marketing strategies, and product positioning**.

---

## 🎯 Business Problem

The retail company wants to better understand changes in purchasing behavior across:

- Demographics
- Product categories
- Sales channels
- Discounts
- Reviews
- Seasons
- Payment/shopping preferences
- Customer subscription status

The main business question is:

> **How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?**

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| 🐍 Python | Data cleaning, preprocessing & feature engineering |
| 🐼 Pandas | Data manipulation and analysis |
| 🐘 PostgreSQL | Database storage and SQL analysis |
| 🗃️ SQL | Business analysis and customer segmentation |
| 📊 Power BI | Interactive dashboard and visualization |
| 🔧 Git & GitHub | Version control and project management |

---

## 📊 Dataset

The dataset contains:

- **3,900 rows**
- **18 columns**
- Customer demographic information
- Product purchase information
- Shopping behavior information
- Review ratings
- Subscription status
- Shipping preferences

### Major Features

#### Customer Information
- Customer ID
- Age
- Gender
- Location
- Subscription Status

#### Purchase Information
- Item Purchased
- Category
- Purchase Amount
- Season
- Size
- Color

#### Shopping Behavior
- Discount Applied
- Promo Code Used
- Previous Purchases
- Frequency of Purchases
- Review Rating
- Shipping Type

There were **37 missing values in the Review Rating column**, which were handled during data preparation. :contentReference[oaicite:1]{index=1}

---

# 🔄 Project Workflow

```text
Raw Dataset
     │
     ▼
Python Data Cleaning
     │
     ▼
Feature Engineering
     │
     ▼
PostgreSQL Database
     │
     ▼
SQL Business Analysis
     │
     ▼
Power BI Dashboard
     │
     ▼
Business Insights & Recommendations
