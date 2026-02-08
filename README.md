# 🛒 Olist E-Commerce Business Analysis (EDA)

This project presents a complete Exploratory Data Analysis (EDA) of the Olist Brazilian E-Commerce Public Dataset.  
The goal of this analysis is to transform raw transactional data into meaningful business insights that support data-driven decision-making.

Using Python and data visualization techniques, this project evaluates revenue performance, customer behavior, logistics efficiency, and operational trends.

---

## 📌 Project Objective

The primary objective of this project is to:

• Analyze overall sales performance  
• Identify top-performing product categories  
• Understand customer purchasing behavior  
• Evaluate delivery efficiency  
• Study payment distribution patterns  
• Generate business-level insights and recommendations  

---

## 📂 Dataset Overview

The Olist dataset contains multiple interconnected tables, including:

- Customers  
- Orders  
- Order Items  
- Payments  
- Reviews  
- Products  
- Sellers  
- Geolocation  

These datasets were merged using common keys such as `order_id`, `customer_id`, and `product_id` to build a unified analytical dataset.

---

## ⚙️ Project Workflow

The analysis was conducted in the following sequence:

1. Data loading and inspection  
2. Data cleaning (handling missing values and duplicates)  
3. Date-time transformation  
4. Multi-table merging  
5. Feature engineering (Revenue, Delivery Time, Date Features)  
6. KPI calculation  
7. Visualization and business interpretation  

---

## 📊 Key Performance Indicators (KPIs)

- Total Revenue  
- Total Orders  
- Total Customers  
- Average Order Value (converted to INR)  
- Average Delivery Time (in days)  
- Repeat Customer Rate  

---

## 📈 Key Insights

- Revenue shows noticeable seasonal variation across months.  
- A small number of product categories generate the majority of total revenue.  
- Credit card is the dominant payment method among customers.  
- Higher delivery times are associated with lower review scores.  
- A limited portion of customers make repeat purchases, indicating retention opportunities.  

---

## 💡 Business Recommendations

- Improve logistics efficiency to reduce delivery time and increase customer satisfaction.  
- Focus marketing efforts on high-performing categories to maximize revenue.  
- Introduce loyalty programs to improve repeat customer rate.  
- Optimize freight costs to improve overall profit margins.  
- Use regional performance data to run targeted state-wise campaigns.  

---

## 🛠 Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🔮 Future Scope

- Customer segmentation using RFM analysis  
- Sales forecasting models  
- Churn prediction  
- Recommendation system  
- Interactive dashboard integration (Power BI / Tableau) 
