# 🛒 Business Performance Analysis – Retail Store Dataset

A data analytics project that explores key business performance metrics using a retail store dataset (from Kaggle). The analysis focuses on sales, profit, customer behavior, delivery methods, and the impact of promotional strategies over the period 2014–2017.

## 📊 Overview

- **Objective:** Identify key factors affecting revenue and profit. Generate insights to support strategic decision-making for sales, marketing, and customer retention.
- **Dataset:** Superstore Sales dataset (9,994 records, 21 fields)
- **Tools Used:** SQL, Power BI, Excel

## ⚙️ Project Steps

1. **Data Cleaning & Preparation**
   - Removed missing values and duplicates
   - Converted date columns for time-based analysis
   - Calculated new features: customer type, first purchase date, delivery duration, etc.

2. **Exploratory Data Analysis (EDA)**
   - Analyzed performance by product categories and sub-categories
   - Segmented customers by behavior (new vs. returning)
   - Evaluated sales by region and state

3. **Insights & Business Recommendations**
   - 📈 **Technology** category delivered the highest profit margin despite lower sales volume
   - 📉 **Furniture** had multiple loss-making products (e.g., Tables, Bookcases)
   - 🔁 High returning customer rate, but significant drop in new customers after 2015
   - 🚚 Most orders used **Standard Class** delivery, yet faster delivery methods were underutilized
   - 💸 Discounts above 20% often led to **negative profit**

## 📌 Key Skills Demonstrated

- Data Cleaning and Transformation (SQL, Power BI)
- Data Visualization and Dashboarding
- Business Performance Metrics
- Profitability and Customer Segmentation
- Analytical Thinking and Insight Generation

## 📷 Sample Visuals
### Sales Overview
![Sales Dashboard](sales_overview.PNG)
Store's products include 3 categories: Technology, Furniture and Office Supplies.
The revenue ratio between categories is not too different (less than 5%).
Store's customer groups include:
- Consumer (accounting for 50.56%)
- Corporate (accounting for 30.74%)
- Home Office (accounting for 17.75%)
### Customer Segmentation
![Customer Dashboard](customer_analytics.PNG)
***Numbers of customer/ Total customers of orderdate Chart***
- Total number of customers increased by 260% from 2014 to 2017.
- The number of new customers decreased by 97.5%: from 121 new customers (2014) to 3 new customers (2017), especially sharply decreased from the third quarter of 2014 to the first quarter of 2015.
=> There is a problem of why the number of new customers decreased in early 2015.

***Retention rate after first order month Chart***
- The rate of returning customers is relatively high, especially in the fourth quarter of the year (>40%).
=> The store has a good customer retention strategy, which helps them increase revenue steadily over the years even though the number of new customers does not increase.
**Top 5 customer by number of order & Top 5 customer by profit Chart**
- Implement incentive programs to attract new customers and retain old customers from regular customers: VIP Member, Refer new customers will get discounts, ...
***Number of customer by state***
- Customers are mainly concentrated in populous states such as: California (577), New York (415), Texas (370), ...
- It is possible to further promote customer attraction in Florida when the population density and total population here are similar to California and New York.
**Sale of Profit by Customer_ID and Type**
Some cases of customers showing unusual signs
=> Need to find out why, is there fraud here?
  
### Product Analytics
![product Chart](product_analytics.PNG)
**Total of Sales/Profit/Quantity by Category Chart**
- Technology category has the highest profit margin (17.40%) despite the small sales volume, which can be explained by the fact that this product group is often of high value
.
- Office Supplies has the second highest profit margin (17.04%) with the largest number of products sold (60.48%).

- Furniture is the product group with the lowest profit margin (2.49%).
**Total Sales/Profit by Category/Sub category Chart**
  Technology:
- Most profitable industry.
- Copiers is the most profitable product group of Technology ($55.6k) despite the lowest revenue ($149k), high profit margin (37.2%).
- Machines group is the least profitable ($3.4k), ~$52k lower than Copiers.
Office supplies:
- Second most profitable category with $122k.
- Paper is the most profitable category ($34k) with high profit margin (43.39%).
- Supplies is the lowest profit margin category and also the loss-making category (-2.55% ~ -$1.2k).
Furniture:
- The lowest profit category (almost 7 times lower ~ $123k than Technology).
- Chairs has the highest profit with $26k.
- Bookcases and Tables are the 2 product groups with loss-making results of -$3.4k and -$17.7k respectively, profit margins of -3.02% and -8.56%.
### Analyze other factors
![Shipment & Discount Chart](shipment&discount.PNG)
**Number of order by Ship mode Chart**
- Standard Class is the most popular delivery method with almost 3k orders (60%), about 2.7k more than Same Day - the least chosen delivery method.
- Second Class and First Class are ranked 2nd and 3rd respectively with about 1k orders and 0.8k orders.
**Number of orders by C_Shiptime and Ship_Mode Chart**
Delivery Time:
- Same Day: < 1 day
- First Class: 1-3 days
- Second Class: 2-5 days
- Standard Class: 4-7 days
**Sum of profit by time and C_isDiscount Chart**
- There are some months where there are a lot of promotional products which leads to low profits.
=> You can find out why there are so many promotions in those months.
**Category, Profit, and Discount Chart**
- With discount <20%, profit is still positive.
- With discount >20%, profit is mostly negative.
=> Need to clearly understand the purpose and evaluate the effectiveness of these promotional programs.

## 📁 Dataset Source

- [Superstore Sales Dataset – Kaggle](https://www.kaggle.com/datasets)

## 👨‍💻 Author

**[Hỏa Ngọc Tú]** - **[SooBul]**
📧 [ngoctu0984339401@gmail.com]

---

