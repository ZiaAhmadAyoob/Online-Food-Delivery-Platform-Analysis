# 🍽️ Online Food Delivery Platform – Data Analysis Case Study

## 📌 Project Overview
This project analyzes customer behavior, restaurant performance, orders, payments, and delivery trends for an online food delivery platform (similar to Foodpanda/UberEats).  
The goal is to extract actionable insights to help management improve delivery efficiency, customer satisfaction, and revenue growth.

---

## 🧭 Objectives
- Clean and preprocess food delivery data for analysis.  
- Explore key metrics like revenue, delivery delays, payment trends, and cuisine popularity.  
- Perform advanced customer segmentation and loyalty analysis.  
- Visualize insights through clear and impactful charts.  
- Provide data-driven recommendations for business growth.

---

## 📂 Dataset
- **Rows:** ~200  
- **Columns:** Customer Info, Restaurant Details, Order Data, Payment Method, Delivery Time, Ratings  
- **File:** `food_delivery_data.csv`

---

## 🛠️ Tools & Libraries
- **Language:** Python  
- **Libraries:** pandas, numpy, matplotlib, seaborn  
- **Environment:** Jupyter Notebook

---

## 🧹 Step 1 – Data Preparation & Cleaning
- Loaded dataset and inspected structure.  
- Handled missing values and removed duplicates.  
- Converted order dates to datetime format.  
- Created new calculated fields:
  - `Delivery Delay (min)` = Delivery Time − Promised Time  
  - `Order Month`  
  - `Day of Week`  
  - `Revenue` = Quantity × Price  

---

## 📊 Step 2 – Exploratory Data Analysis (EDA)
Key analyses performed:
- Most popular cuisine types 🍕🍔🥡  
- Average delivery delay by city 🕒  
- Top 5 restaurants by total revenue 🏆  
- Distribution of payment methods 💳💵  
- Average order value by customer age groups 👥  
- Peak ordering days of the week 📅  
- Monthly revenue trend 📈  
- Average ratings by cuisine type ⭐  
- % of orders delivered late vs on-time 🚴  
- Correlation between delivery time & customer rating 🔗

---

## 🔍 Step 3 – Advanced Analysis
- Top 10 loyal customers (by number of orders)  
- City with highest average order value  
- Premium vs Non-premium restaurant revenue comparison  
- Effect of delivery delays on customer ratings  
- Customer segmentation into **Low**, **Medium**, and **High spenders**

---

## ⚖️ Step 4 – Comparison Insights
- **Cash vs Digital Payments**: Analyzed late delivery trends by payment type.  
- **Age vs Cuisine Preference**: Compared food preferences of customers aged 40+ vs younger segments.

---

## 📈 Step 5 – Visualizations
The project includes 10+ insightful charts:
- Bar charts → Top restaurants, cuisine popularity  
- Line graphs → Monthly revenue, daily orders trend  
- Pie charts → Payment methods, cuisine distribution  
- Histograms → Order value distribution, age groups  
- Heatmap → Correlation between revenue, delay, ratings

---

## 📌 Key Business Insights
- Pizza & Desi cuisines dominate order volume.  
- Digital payments show lower late delivery rates compared to cash.  
- Premium restaurants (rating > 4.5) generate significantly higher revenue.  
- Peak ordering happens on weekends, especially Fridays.  
- Delivery delays negatively impact customer ratings.

---

## 🚀 Recommendations
- ✅ Incentivize digital payments to reduce delays.  
- 🍔 Partner with top cuisines & restaurants to maximize revenue.  
- ⏰ Optimize delivery logistics during peak hours/weekends.  
- 🧍‍♂️ Target high-spending loyal customers with retention offers.  
- ⭐ Encourage premium restaurants to maintain high ratings for better revenue.

---


---

## 📝 Author
**📊 Data Analyst:** [Your Name]  
🔗 LinkedIn: [Your LinkedIn Profile]  
💻 GitHub: [Your GitHub Profile]

---
