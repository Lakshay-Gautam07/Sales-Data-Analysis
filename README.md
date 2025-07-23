# 🧮 Diwali Sales Data Analysis

This project performs an in-depth analysis of Diwali sale data using Python to uncover valuable business insights and purchasing trends. The goal is to support data-driven decision-making for future marketing campaigns and sales strategies.

---

## 🎯 Motivation

Understanding customer purchasing behavior during festive sales like Diwali can help businesses:

- Optimize product inventory
- Tailor marketing strategies
- Identify high-value customer segments
- Maximize profitability and sales conversion rates

---

## 📂 Data Source

- Dataset: `Diwali_Sales_Data.csv`
- Contains customer-level purchase records during a Diwali sale campaign
- Key columns:
  - `Gender`, `Age Group`, `State`, `Product Category`
  - `Amount`, `Orders`, `Marital Status`, `Occupation`

---

## 🧹 Data Cleaning & Preparation

Steps followed before analysis:

- Removed null values
- Converted data types (e.g., `Amount` to numeric)
- Filtered out irrelevant or inconsistent entries
- Standardized column names for easier handling

---

## 📊 Exploratory Data Analysis (EDA)

Performed extensive EDA using:

- **Pandas**: for data wrangling and summarization
- **Seaborn & Matplotlib**: for bar charts, histograms, heatmaps, and pie charts

Key visualizations included:

- Top 10 states by total sales
- Gender-wise and age-wise purchase behavior
- Marital status vs. total spending
- Occupation and product category trends
- Heatmaps for correlation analysis

---

## 🧠 Key Business Insights

- **Female shoppers** (especially aged 26–35) were the most active buyers.
- **Married individuals** spent more on average than unmarried ones.
- **Maharashtra**, **Karnataka**, and **Uttar Pradesh** topped in sales.
- **Electronic Accessories** and **Clothing** were the most popular categories.
- **Working professionals and students** were major contributors to revenue.

---

## 💼 Business Recommendations

- Focus marketing campaigns on married women aged 26–35.
- Ensure high inventory for Electronics and Fashion categories during sales.
- Run state-specific promotions in high-performing regions.
- Offer bundled discounts for students and professionals.

---

## 🚀 How to Run the Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/LG10-main.git
   cd Sales-Data-Analysis-main
