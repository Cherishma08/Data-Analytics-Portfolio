# Data-Analytics-Portfolio
# 🛍️ Customer Shopping Behavior Analysis

## 📌 Project Overview
This project analyzes customer shopping behavior using transactional retail data to uncover insights into spending patterns, customer segments, product preferences, and subscription behavior. The goal is to help businesses improve customer engagement, optimize marketing strategies, and increase revenue.

The analysis combines Python (data preparation), SQL (business analysis), and Power BI (visualization) to create a complete end-to-end analytics solution.

---

## 🎯 Business Problem
A retail company wants to better understand customer purchasing behavior across demographics, product categories, and sales channels. The objective is to identify key factors such as discounts, reviews, seasons, and payment preferences that influence purchasing decisions and repeat customers.

**Main Question:**
How can consumer shopping data be leveraged to identify trends, improve customer engagement, and optimize marketing strategies?

---

## 📊 Dataset Summary
- Total Records: 3,900 purchases  
- Total Columns: 18 features  
- Customer Demographics: Age, Gender, Location, Subscription Status  
- Purchase Details: Item, Category, Amount, Season, Size, Color  
- Shopping Behavior: Discounts, Ratings, Shipping Type, Frequency  
- Missing Values: Review Rating column (handled during preprocessing)  

---

## 🧹 Data Preparation (Python)
Data cleaning and preprocessing steps:

- Loaded dataset using Pandas  
- Handled missing values in review ratings  
- Standardized column names  
- Created age_group feature  
- Created purchase frequency feature  
- Removed redundant columns  
- Exported cleaned data to PostgreSQL database  
- Performed consistency checks  

---

## 🗄️ Data Analysis (SQL)
Business questions answered using SQL:

- Revenue by Gender  
- High-spending discount users  
- Top-rated products  
- Shipping type comparison  
- Subscribers vs Non-subscribers  
- Discount-dependent products  
- Customer segmentation (New / Returning / Loyal)  
- Top products per category  
- Repeat buyers and subscriptions  
- Revenue by age group  

---

## 📈 Power BI Dashboard
Interactive dashboard includes:

- Sales overview  
- Revenue by category  
- Customer segmentation  
- Subscription analysis  
- Discount impact  
- Purchase frequency  
- Top performing products  
- Demographic insights  

---

## 💡 Key Insights
- Subscribers spend more than non-subscribers  
- Loyal customers generate highest revenue  
- Discounts increase purchase frequency  
- Express shipping customers spend more  
- Certain categories dominate total revenue  
- High-rated products drive repeat purchases  

---

## 🚀 Business Recommendations
- Introduce customer loyalty programs  
- Promote subscription benefits  
- Optimize discount strategy  
- Highlight top-rated products  
- Target high-value customer segments  
- Improve marketing personalization  

---

## 🛠️ Tools & Technologies
- Python (Pandas, NumPy)  
- PostgreSQL / SQL  
- Power BI  
- GitHub  
- Data Visualization  
- Exploratory Data Analysis  

---

## 📂 Project Structure
```
Customer-Shopping-Behavior-Analysis
│
├── data
├── python_scripts
├── sql_queries
├── customer_behavior_dashboard.pbix
├── README.md
└── project_report.pdf
```

---

## 📌 Project Workflow
Raw Data → Python Cleaning → SQL Analysis → Power BI Dashboard → Business Insights

---

## 👩‍💻 Author
Cherishma Earle
Customer Shopping Behavior Analysis Project
