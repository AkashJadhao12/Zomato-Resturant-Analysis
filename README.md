# Zomato Restaurant Data Analysis - Project README

## 📌 Project Overview

The **Zomato Restaurant Data Analysis** project demonstrates an end-to-end data analytics workflow—from relational database management to SQL querying, data visualization via Power BI dashboards, and actionable business intelligence reporting.

The primary objective is to analyze Zomato's operational and transactional data to uncover critical business insights regarding customer ordering behaviors, cuisine preferences, restaurant performance metrics, and revenue distribution.

---

## 👥 Project Team: **Select Star ⭐**

* **Yukta Jaysingpure**

* **Monika Mengawade**

* **Akash Jadhao**

* **Revan Gunjal**


---

## 🔄 Analytical Workflow

1. **Dataset & Schema Design**: Built and normalized a MySQL relational database modeling Zomato's ecosystem across multiple core tables.


2. **SQL Analysis**: Executed targeted SQL queries using aggregate functions (`SUM`, `COUNT`, `AVG`), joins, subqueries, and window functions to extract critical patterns.


3. **Dashboard & Visualization**: Integrated comprehensive Power BI and executive dashboards to visualize KPI performance, monthly trends, city-wise demand, and restaurant ratings.


4. **Insights & Recommendations**: Translated quantitative findings into strategic business actions to mitigate customer satisfaction risks and maximize revenue potential.



---

## 📊 Database Schema & Table Inventory

| Table Name | Row Count | Column Count | Key / Relationships |
| --- | --- | --- | --- |
| **users** | 100,000

 | 10

 | `user_id` (Primary Key)

 |
| **restaurant** | 148,541

 | 12

 | `id` / `restaurant ID` (Primary Key)

 |
| **orders** | 150,281

 | 6

 | `user_id` & `r_id` (Foreign Keys)

 |
| **menu** | 1,179,936

 | 5

 | `menu_id` (Primary Key), `r_id`, `f_id` (Foreign Keys)

 |
| **food** | 371,561

 | 3

 | `f_id` (Primary Key)

 |

---

## 💡 Key Business Findings & Insights

* **Top-Selling Restaurants**: A select few high-performing restaurants drive a major portion of total marketplace revenue.


* **Cuisine Demand**: Popular high-demand groupings (such as North Indian and Chinese variants) capture the largest segment of customer orders.


* **Customer Retention**: Analysis highlights active pools of repeat customers versus one-time users, emphasizing the importance of targeted loyalty and retention campaigns.


* **Rating Impact & Anomalies**: Restaurants maintaining higher customer ratings (4.0+) capture significantly higher order volumes, though specific high-revenue outliers with low ratings require immediate service quality audits.



---

## 🚀 Recommendations

* **Quality Assurance**: Proactively investigate low-rated restaurants that generate substantial revenue to protect brand reputation and food quality consistency.


* **Targeted Marketing**: Expand promotional campaigns and partner availability for top-performing cuisines within high-demand urban centers.


* **Customer Retention Programs**: Implement automated engagement strategies to convert one-time ordering users into repeat customers.
