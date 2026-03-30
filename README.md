# 📉 Customer Retention & Churn Analytics Dashboard | Power BI, SQL, DAX

This project presents an end-to-end analytics workflow for analyzing customer retention, churn behavior, and customer lifetime value (CLV) using SQL, Power BI, DAX, and Power Query.

The goal is to help decision-makers better understand customer behavior, identify churn risks, and monitor key retention KPIs through an interactive dashboard.

---

## 🚀 Project Overview

In competitive markets, retaining existing customers is often more cost-effective than acquiring new ones. This project was designed to analyze customer retention and churn patterns through an interactive Power BI dashboard supported by SQL-based data preparation.

The dashboard helps answer questions such as:

- How many customers are active versus churned?
- Which customer groups are more likely to churn?
- How do repeat customers differ from one-time buyers?
- What patterns can support better retention strategies?

---

## 🔧 Tech Stack

- **SQL** – data extraction, cleaning, transformation, and churn-related analysis
- **Power BI** – data modeling, dashboard development, and interactive reporting
- **DAX** – custom measures for retention KPIs, churn rate, and customer activity
- **Power Query** – ETL workflow for preparing and shaping the dataset

---

## 📌 Key KPIs Tracked

- Total Customers
- Active Customers
- Churned Customers
- Churn Rate
- Retention Rate
- Repeat Customer Rate
- Estimated Customer Lifetime Value (CLV)

---

## 💼 Business Value

This dashboard can support decision-makers by:

- monitoring churn and retention trends
- identifying at-risk customer groups
- comparing customer segments based on behavior and value
- supporting more targeted retention and engagement strategies

---

## 📊 Key Insights

- Approximately **30% of customers** were identified as churned based on the project’s churn definition.
- **Repeat customers** showed significantly higher estimated lifetime value compared to one-time buyers.
- Customer retention patterns varied across segments, with some groups showing more stable repeat behavior.

---

## 🧠 SQL Analysis

SQL was used to prepare customer-level insights, including:

- identifying active versus churned customers
- calculating repeat purchase behavior
- aggregating transaction-level data into customer KPIs

Example query:

```sql
SELECT customer_id,
       COUNT(order_id) AS total_orders,
       MAX(order_date) AS last_order_date
FROM orders
GROUP BY customer_id;
## 🗂 Project Structure

- **/Dataset** – original customer dataset (CSV)
- **/SQL** – SQL queries used for customer activity and churn analysis
- **/PowerBI_Files** – Power BI dashboard file (.pbix)
- **/Images** – screenshots of the final dashboard
- **README.md** – project documentation

---

## 📸 Dashboard Preview

![Dashboard Overview](Images/dashboard-overview.png)
![Retention Analysis](Images/retention-analysis.png)

> Make sure the image filenames in your repository match the names above.  
> If your current screenshot filenames are different, either rename the files or update the image paths here.

---

## ▶️ How to Use

1. Review the dataset in the `/Dataset` folder
2. Check the SQL scripts in the `/SQL` folder
3. Open the Power BI file from `/PowerBI_Files`
4. Explore the dashboard pages and KPI measures

---

## ✅ Conclusion

This project shows how SQL and Power BI can be combined to analyze customer behavior, measure churn and retention, and support better business decisions through interactive reporting.

---

## 👤 Author

**Seyed Iman Tahami**  
Data Analyst | BI & Customer Analytics

- [LinkedIn](https://www.linkedin.com/in/itahami/)
- [GitHub](https://github.com/imantahami)

If you found this project useful, consider giving it a ⭐
