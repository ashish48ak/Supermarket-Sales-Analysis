# 🛒 Supermarket Sales Analysis

Supermarkets are an essential part of our daily lives, providing food and essentials we need every day.  
With the growth of **online grocery applications**, every transaction is digitally recorded, generating **rich datasets** that reveal customer behavior, sales patterns, and profitability insights.  

This project leverages supermarket transaction data to explore **sales trends, customer preferences, and profit drivers**—helping us understand how well the business is performing.

---

## 📊 Dataset

- **Source:** [Kaggle – Supermart Grocery Sales Dataset](https://www.kaggle.com/datasets/mohamedharris/supermart-grocery-sales-retail-analytics-dataset)  
- **Region Covered:**  India  
- **Details:** The dataset includes transactional-level information such as:
  - Customer details  
  - Product categories & subcategories  
  - Sales, discounts, and profit margins  
  - Order dates, regions, and cities  

---

## 🎯 Problem Statement

Analyze supermarket sales data to **identify key factors influencing sales and profitability**.  
The goal is to provide insights that improve **operational efficiency** and **maximize profit**.

---

## 📑 Table of Contents

1. [Environment Setup](#-environment-setup)  
2. [Libraries Required](#-libraries-required)  
3. [Getting Started](#-getting-started)  
4. [Project Workflow](#-project-workflow)  
5. [Data Visualization](#-data-visualization)  
6. [Conclusion](#-conclusion)  

---

## ⚙️ Environment Setup

You’ll need **Jupyter Notebook** to run this project.

- Install Jupyter:
```bash
pip install notebook
Run Jupyter:

jupyter notebook

📦 Libraries Required

Install the following libraries before running the project:

pip install numpy
pip install pandas
pip install matplotlib
pip install seaborn

🚀 Getting Started

Clone this repository to your local machine:

git clone https://github.com/ashish48ak/Supermarket-Sales-Analysis.git


Open the Jupyter Notebook and follow the steps for analysis.

🔎 Project Workflow
1. Importing Libraries

NumPy, Pandas, Matplotlib, Seaborn

2. Reading Data

Using pd.read_csv() to load the dataset

3. Dataset Overview

Shape & size of data

Data types (numerical, categorical, text)

Info using df.info()

4. Data Preprocessing

Checked and confirmed no null values

Converted order_date to datetime format

Extracted year, month, day from date

Calculated discount_amount

5. Statistical Insights

Products sold by category, subcategory, city, region

Sales and profit trends by year, month, day

Top-performing customers

6. Data Visualization

Multiple visualizations to uncover patterns:

📦 Products sold by category, subcategory, region, city

💰 Total sales by category, region, city, month, year

📈 Total profit across multiple dimensions

🏆 Top customers by sales & profit

🎟️ Discounts availed

📉 Data Visualization Highlights

Sales Distribution by Category & Subcategory

Regional & City-level Sales Patterns

Monthly & Yearly Sales Trends

Profitability Analysis

Top Customers by Sales & Profit

Discount Utilization Analysis

(All charts available in the notebook)




🏁 Conclusion

Key findings from the analysis:

📊 Analyzed 9000+ customer transactions

🍫 Snacks made up over 15% of sales, showing strong demand

🌍 West region contributed 32% of total sales, the top-performing region

🥤 Within beverages, Health Drinks & Soft Drinks were the most profitable

📅 November contributed ~15% of yearly profit → best month for promotions

📜 License

This project is licensed under the MIT License – feel free to use, share, and adapt with attribution.

<div align="center">

✨ This project demonstrates how data analysis can uncover valuable insights in retail sales. ✨

🔝 Back to Top

</div> ```
