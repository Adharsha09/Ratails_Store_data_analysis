Target Retail Store - Business Insights & Data Analysis

📌 Project Overview

This project analyzes e-commerce sales data from Target's operations in Brazil using SQL-based data analysis. The goal is to extract meaningful insights, identify key trends, and provide data-driven recommendations to improve business strategies.

📂 Dataset Information

The dataset consists of multiple tables containing:

1.  customers: Customer details (ID, location, etc.).

2. orders: Order details, timestamps, and statuses.

3. order_items: Product details, prices, and freight values.

4. payments: Payment methods and installment details.

5. order_reviews: Customer feedback and ratings.

5. geolocation:Lattitude,logitude , State , City & Zip_Code.

6. products: Product details (ID , Category, Photos Count, Etc)

7. Sellers : Seller details (ID, City, State, Zip_Code)

📊 Key Analysis Performed

1️⃣ Initial Exploration

	Time range analysis: Identified first and last order dates.

	Customer distribution: Orders received from 4,119 cities across 27 states.

	Review distribution: Most orders received 5-star ratings.


2️⃣ Sales & Growth Trends

	Year-over-Year (YoY) Growth: 19.72% increase in orders from 2017 to 2018.

	Monthly seasonality: Orders peak in May, July, and August.

	Peak order time: Majority of orders placed between 1 PM – 6 PM.


3️⃣ Regional Sales Analysis

	State-wise distribution: SP has the highest sales; RR, AP, and AC have the lowest.

	Freight costs: RR has the highest average freight cost but low total expenditure.


4️⃣ Payments Analysis

	Payment method usage: 76.94% of transactions were made via credit card.

	Installments trend: 51,170 orders were paid through EMI.


5️⃣ Delivery & Logistics Optimization

	Longest delivery: 210 days; some orders were fulfilled 188 days late.

	Fastest states: AL state customers received orders ~7.9 days earlier than expected.


✅ Recommendations

✔ Leverage Peak Seasons: Implement targeted promotions in May, July, and August.

✔ Boost Off-Peak Sales: Offer cashback/discounts in September & October.

✔ Expand in Low-Performing States: Focus on increasing sales in RR, AP, AM, AC, RO, and TO.

✔ Reduce Delivery Delays: Optimize supply chain & introduce real-time tracking.

✔ Optimize Freight Costs: Negotiate better shipping rates & implement bulk shipping discounts.

✔ Promote EMI & Alternative Payment Methods: Increase awareness of installment plans & offer incentives for UPI and voucher payments.

🛠️ Installation & Setup

Clone the repository:

git clone https://github.com/Adharsha09/Ratails_Store_data_analysis.git
cd your-repo-name

Set up the database connection:

Use Google BigQuery or any SQL-based tool to execute queries.

Import dataset tables into your database.

Run SQL Queries:

Queries are available in the SQL_Scripts folder.

Execute queries sequentially to generate insights.

📜 SQL Queries Used

orders_analysis.sql: Time range, order trends, and seasonality.

regional_sales.sql: State-wise sales and freight analysis.

payments_analysis.sql: Payment method usage and EMI analysis.

delivery_logistics.sql: Delivery time and freight cost insights.

🎯 Conclusion

This project provides actionable insights to enhance business performance, optimize logistics, and improve customer satisfaction. The SQL-based approach enables data-driven decision-making, helping Target strengthen its e-commerce strategy in Brazil.

📌 
📧 Email: adharsha.t.n@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/datawithadharsha/

🐙 GitHub: https://github.com/Adharsha09


 
