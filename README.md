# E-Commerce Data Analysis

## 📊 Project Overview

This project analyzes e-commerce business performance across orders, revenue, customers, product categories, fulfillment, demographics, geography, and yearly trends.

The analysis covers **10,000 orders** and **6,000 unique customers** for the period **FY2024–2026**.

The objective is to identify important business trends, customer behavior, category performance, operational issues, and opportunities for business growth using Python.

---

## 🎯 Business Objectives

* Analyze overall e-commerce sales and order performance
* Understand customer purchasing behavior
* Compare product category performance
* Identify high-performing geographic regions
* Analyze customer segments and demographics
* Evaluate order fulfillment performance
* Analyze discounts and revenue efficiency
* Identify data-quality issues
* Study year-over-year business trends
* Generate actionable business recommendations

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas** – Data cleaning, transformation, and analysis
* **Matplotlib** – Data visualization
* **Jupyter Notebook** – Analysis and documentation
* **CSV** – Dataset format

---

## 📁 Dataset

The project uses two simulated datasets:

* `ecommerce_customers.csv` – Customer information and demographic details
* `ecommerce_orders.csv` – Order, revenue, category, quantity, location, discount, and fulfillment information

The datasets contain simulated data created for learning and portfolio purposes.

---

## 🔍 Analysis Performed

### 1. Overall Business Performance

Key performance indicators:

| KPI                 |     Value |
| ------------------- | --------: |
| Total Orders        |    10,000 |
| Unique Customers    |     6,000 |
| Total Revenue       | ₹33.24 Cr |
| Average Order Value |   ₹33,244 |
| Units Sold          |    30,164 |

---

### 2. Product Category Analysis

The analysis compares:

* Orders by category
* Revenue by category
* Units sold
* Discount given
* Revenue per unit

**Fashion** generated the highest revenue with approximately **₹4.96 Cr** and recorded **1,501 orders**.

The overall category mix is well diversified, with relatively small differences between the highest- and lowest-performing categories.

---

### 3. Geographic Analysis

Tamil Nadu is the strongest market, contributing approximately **48.5% of total orders**.

Other major states include:

* Maharashtra
* Karnataka
* West Bengal
* Telangana
* Delhi

The analysis also examines city-level order and revenue performance.

---

### 4. Customer Segment Analysis

Customers are divided into:

* Regular
* Premium
* VIP

Regular customers generate the majority of orders and revenue.

An important finding is that the average order value is relatively similar across all three segments, suggesting that VIP customers may have an opportunity to increase their purchase frequency.

---

### 5. Order Fulfillment Analysis

Order status was analyzed across:

* Delivered
* Shipped
* Processing
* Returned
* Cancelled

**6,866 orders (68.7%)** were delivered successfully.

Returned and cancelled orders together represent approximately **13.9% of total orders**, highlighting an opportunity to investigate fulfillment and customer-experience issues.

---

### 6. Customer Demographics

Customer behavior was analyzed by:

* Age group
* Gender
* Customer segment

The analysis identified lower order activity among the **18–25** age group and no recorded orders for the **66+** group, which should be verified against the source data.

---

### 7. Discount Analysis

Discount performance was compared across product categories.

Fashion had the highest discount rate at approximately **14.5%**, while Electronics and Grocery had comparatively lower discount rates.

This provides an opportunity to evaluate whether Fashion promotions can be optimized while maintaining sales volume.

---

### 8. Year-over-Year Analysis

Revenue and order performance were compared across FY2024, FY2025, and FY2026.

| Year | Orders |   Revenue |
| ---- | -----: | --------: |
| 2024 |  3,741 | ₹12.50 Cr |
| 2025 |  3,721 | ₹12.36 Cr |
| 2026 |  2,538 |  ₹8.38 Cr |

2024 and 2025 show relatively flat performance, while 2026 represents a partial year and should be evaluated again after the complete year's data is available.

---

## 💡 Key Business Insights

1. **Tamil Nadu is the dominant market**, contributing approximately 48.5% of total orders.
2. **Fashion is the leading category** by both order volume and revenue.
3. The business has a **diversified product-category mix** without heavy dependence on one category.
4. **Regular customers drive the majority of revenue and orders.**
5. VIP customers have relatively low order frequency despite having competitive average order value.
6. **68.7% of orders were delivered successfully.**
7. Returned and cancelled orders account for approximately **13.9% of orders**, requiring further investigation.
8. Fashion has the **highest discount intensity**, creating a potential margin-optimization opportunity.
9. Revenue per unit is relatively consistent across categories, suggesting that **basket-size growth and cross-selling** may be more effective than relying mainly on price increases.
10. Small data-quality gaps exist in fields such as delivery city and gender.

---

## 📌 Business Recommendations

* Expand marketing and logistics investment beyond Tamil Nadu to reduce geographic concentration.
* Investigate returned and cancelled orders by category and region.
* Review Fashion discount strategies to improve margin efficiency.
* Increase VIP purchase frequency through loyalty and targeted engagement campaigns.
* Improve customer address and demographic data capture.
* Investigate the absence of the 66+ customer group.
* Improve engagement and acquisition among younger customers.
* Monitor the flat 2024–2025 performance as 2026 data becomes complete.
* Focus on cross-selling, bundling, and increasing basket size.

---

## 📂 Project Files

```text
Ecommerce-Data-Analysis/
│
├── ecommerce_analysis.ipynb
├── ecommerce_customers.csv
├── ecommerce_orders.csv
├── Business_Insights.md
└── README.md
```

---

## 📈 Project Outcome

This project demonstrates practical data-analytics skills including:

* Data loading
* Data cleaning
* Exploratory Data Analysis (EDA)
* Data transformation
* Aggregation
* Business KPI analysis
* Data visualization
* Customer analysis
* Revenue analysis
* Geographic analysis
* Fulfillment analysis
* Business insight generation
* Data-driven recommendations

The project was created as a portfolio project to demonstrate practical **Python-based data analysis and business intelligence skills**.
