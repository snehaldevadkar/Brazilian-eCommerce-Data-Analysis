# 🇧🇷 Brazilian E-Commerce Data Analysis

> **Exploratory Data Analysis of Brazilian e-commerce performance, customer behavior, payments, delivery, and satisfaction.**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge\&logo=pandas\&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge\&logo=numpy\&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge\&logo=python\&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge\&logo=jupyter\&logoColor=white)

---

## 📌 Project Overview

This project explores the **Brazilian Olist e-commerce dataset** to uncover patterns in sales, customers, products, payments, delivery performance, customer satisfaction, and order cancellations.

The analysis focuses on turning raw transactional data into **business-relevant insights** that can help understand:

* 📈 Sales and revenue performance
* 🌎 Customer distribution across Brazil
* 🛍️ Product category performance
* 💳 Payment methods and installment behavior
* 🚚 Delivery efficiency
* ⭐ Customer satisfaction
* ❌ Order cancellations

---

## 🎯 Business Questions

The analysis was designed around the following questions:

1. How do orders and revenue change over time?
2. Which Brazilian states generate the most revenue?
3. Which product categories contribute the most revenue?
4. What payment methods do customers prefer?
5. How does installment behavior vary by payment type?
6. Does delivery time affect customer satisfaction?
7. Which states have the highest number of cancelled orders?

---

## 📊 Dataset at a Glance

| Metric                            |                     Result |
| --------------------------------- | -------------------------: |
| 🛒 Total Orders                   |                 **99,441** |
| ❌ Cancellation Rate               |                 **~0.63%** |
| 🏆 Top Revenue State              |         **São Paulo (SP)** |
| 🥇 Top Revenue Category           | **Beauty & Personal Care** |
| 💳 Dominant Payment Method        |            **Credit Card** |
| 🚚 Delivery vs Review Correlation |                **~ -0.33** |

---

## 🔎 Key Insights

### 🛒 Sales Performance

* The dataset contains **99,441 orders**.
* Monthly orders and revenue generally increased throughout the observed period.
* Strong performance was observed around **late 2017 and early 2018**.

### 🌎 Geographic Performance

* **São Paulo (SP)** has the largest customer base and generates the highest total revenue.
* Other major markets include **Rio de Janeiro (RJ)** and **Minas Gerais (MG)**.
* Revenue is strongly concentrated in states with larger customer populations.

### 🛍️ Product Performance

* **Beauty & Personal Care (`beleza_saude`)** is the highest-revenue product category among the analyzed categories.
* Product-category analysis helps identify which segments contribute most to overall revenue.

### 💳 Payment Behavior

* **Credit cards** are the dominant payment method.
* Single-payment transactions represent a significant share of purchases.
* Credit-card users account for most installment activity.

### 🚚 Delivery & Customer Satisfaction

One of the strongest findings from the analysis is the relationship between delivery time and customer satisfaction.

**Delivery time and review score show a negative correlation of approximately -0.33.**

| Review Score | Average Delivery Time |
| -----------: | --------------------: |
|          ⭐ 5 |        **~10.2 days** |
|          ⭐ 1 |        **~20.8 days** |

This suggests that **longer delivery times are associated with lower customer review scores**.

> ⚠️ **Important:** Correlation does not prove that delivery time alone causes lower ratings. Other factors may also influence customer satisfaction.

### ❌ Order Cancellations

* The overall cancellation rate is approximately **0.63%**.
* Cancelled orders are concentrated in larger customer markets.
* **SP, RJ, and MG** account for a significant share of cancelled orders.

---

# 📈 Visualizations

### Monthly Revenue Trend

![Monthly Revenue Trend](monthly_revenue_trend.png)

### Top 10 Product Categories by Revenue

![Top 10 Product Categories by Revenue](top_10_product_categories_revenue.png)

### Top 10 States by Revenue

![Top 10 States by Revenue](top_10_states_revenue.png)

### Revenue by Payment Type

![Revenue by Payment Type](revenue_by_payment_type.png)

### Average Delivery Time by Review Score

![Average Delivery Time by Review Score](average_delivery_time_review_score.png)

---

## 🧰 Tools & Technologies

| Tool                    | Purpose                      |
| ----------------------- | ---------------------------- |
| 🐍 **Python**           | Data analysis                |
| 🐼 **Pandas**           | Data manipulation & analysis |
| 🔢 **NumPy**            | Numerical operations         |
| 📊 **Matplotlib**       | Data visualization           |
| 📓 **Jupyter Notebook** | Analysis environment         |

---

## 📂 Project Structure

```text
Brazilian-E-Commerce-Data-Analysis/
│
├── 📁 Data/
│   └── Dataset files
│
├── 📓 Olist_EDA.ipynb
│
├── 📊 monthly_order_trend.png
├── 📈 monthly_revenue_trend.png
├── 🛍️ top_10_product_categories_revenue.png
├── 🌎 top_10_states_customers.png
├── 💰 top_10_states_revenue.png
├── 📊 top_states_avg_revenue.png
├── 📊 top_states_avg_revenue_500_customers.png
├── 💳 revenue_by_payment_type.png
├── 💳 average_installments_payment_type.png
├── 💰 average_payment_value_installments.png
├── ⭐ lowest_rated_product_categories.png
├── 🚚 average_delivery_time_review_score.png
├── ❌ cancelled_orders_by_state.png
│
└── 📄 README.md
```

---

## 💡 Business Takeaways

The analysis highlights several areas that could matter from a business perspective:

### 1. 🚚 Improve Delivery Performance

The negative relationship between delivery time and review scores suggests that improving delivery efficiency could potentially improve customer satisfaction.

### 2. 🌎 Focus on High-Value Markets

São Paulo and other major states represent important revenue markets and deserve continued attention from sales and logistics teams.

### 3. 💳 Optimize Payment Experience

Credit cards dominate customer payments, making the payment experience and installment options important areas for optimization.

### 4. 🛍️ Monitor High-Revenue Categories

High-performing categories such as Beauty & Personal Care can be analyzed further for pricing, inventory, marketing, and customer retention opportunities.

### 5. ❌ Monitor Cancellation Patterns

Although the cancellation rate is relatively low, geographic concentration can help identify markets where operational issues may require additional investigation.

---

## 🧠 What I Learned

Through this project, I practiced:

* Data cleaning and preprocessing
* Exploratory data analysis
* Aggregation and grouping with Pandas
* Time-series analysis
* Geographic analysis
* Payment behavior analysis
* Correlation analysis
* Data visualization
* Extracting business insights from raw data
* Communicating analytical findings through a GitHub project

---

## 🏁 Conclusion

This project demonstrates how exploratory data analysis can be used to understand **e-commerce performance beyond basic sales numbers**.

The analysis identified important patterns across revenue, geography, product categories, payment behavior, delivery performance, customer satisfaction, and cancellations.

The most notable finding is the relationship between **delivery time and customer review scores**, where longer delivery times are associated with lower ratings.

Overall, the project shows how data can be transformed into **clear business insights that support better decisions around sales, logistics, customer experience, and market performance.**

---

## 👤 Author

### **Snehal Devadkar**

**Aspiring Data Analyst | Python | SQL | Power BI | Excel**

📌 This project is part of my **Data Analytics portfolio** and demonstrates my ability to analyze real-world datasets and communicate business insights through data.

---

⭐ **If you found this project useful, feel free to explore the notebook and visualizations.**
