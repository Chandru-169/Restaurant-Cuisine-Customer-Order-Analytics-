
This project presents an end-to-end data analysis and visualization of restaurant customer orders using **Advanced SQL** and **Power BI**. The goal is to uncover actionable insights into cuisine popularity, promo code effectiveness, customer behavior, and restaurant performance.

**Table of Contents**

1. Project Objective
2. Business Questions Addressed and Key Metrics Derived Using Advanced SQL
3. Power BI Visualization for Key Insights
4. Summary of Analytical Insights
5. Strategic Takeaways

**Project Objectives**

1. Perform Exploratory Data Analysis (EDA) to get familiar with the dataset: its size, shape, data types, and structure
2. Perform advanced SQL analytics on restaurant order data to derive business insights using MySQL
3. Perform comprehensive analysis of customer order data across multiple restaurant cuisines using Power BI
4. To uncover actionable insights that can inform strategic decisions in restaurant operations, marketing, and customer engagement

**Business Questions Addressed and Key Metrics Derived Using Advanced SQL**

Utilized advanced SQL techniques including **aggregate functions, window functions, joins, subqueries, conditional logic, sorting, date/time operations, and data filtering** to address and solve key business scenarios outlined in the analysis.

1. **Top 3 Restaurants per Cuisine**: Identified using ROW_NUMBER() over partitioned cuisine groups
2. **Daily Customer Metrics**: Tracked total and new customers per day using nested queries and date comparisons
3. **One-Time January Customers**: Customers who ordered only once in Jan 2025 and never again
4. **Dormant Customers**: Customers with no orders in the last 7 days but acquired via promo a month ago
5. **Every 3rd Order Tracker**: Used to trigger personalized messages after every 3rd order
6. **Promo-Only Loyal Customers**: Identified customers who placed multiple orders, all with promo codes
7. **Promo-Free First Orders**: Calculated percentage of customers acquired without using a promo code

Additionally, key metrics such as **Total Orders, Weekend Orders, Week Orders, Promo Orders, % of Weekend, % of Promo Orders** derived.

**Power BI Visualization for Key Insights**

Leveraged Power BI capabilities to create calculated columns and measures using **DAX** functions. Developed a **variety of visualizations including line and stacked column charts, stacked bar charts, ribbon charts, matrix tables, KPI cards, pie charts, and donut charts** to effectively communicate key insights and performance indicators.

1. **Identifying the most popular cuisines** based on order volume
2. **Evaluating the effectiveness of promotional codes** across different cuisines and customer segments
3. **Analyzing restaurant-level performance** in terms of order count and promotional uptake
4. **Understand customer behavior patterns** including order frequency, cuisine diversity, and promo code adoption
5. **Track order trends over time** including weekly and weekend-based variations
6. **Support data-driven decision-making** for marketing, menu optimization, and customer retention strategies

   **Dashboard Screenshots**

   ![Screenshot 2025-05-26 211008](https://github.com/user-attachments/assets/b4fe3455-4bc7-486d-bffb-97aba7fde609)

   
   ![Screenshot 2025-05-26 211153](https://github.com/user-attachments/assets/887babda-9cbb-4a7f-a66b-de45cf42bc49)

   **Summary of Analytical Insights**

   ![Screenshot 2025-05-26 211359](https://github.com/user-attachments/assets/a803b10e-edd3-4ac8-b761-90fdcd768135)

   **Strategic Takeaways**

1. **Lebanese cuisine** is the most popular and has the highest promo usage
2. **Promo codes** significantly influence order volume
3. **Customer retention** is low — most customers order only once
4. **Weekend orders** are relatively low, suggesting an opportunity for targeted weekend promotions
      
