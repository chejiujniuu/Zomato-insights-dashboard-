## Objectives
- Track order and delivery performance.
- Monitor restaurant reviews and ratings.
- Understand customer behavior and preferences.
- Visualize data for quick decision-making.
- Enhance operational efficiency using key performance indicators (KPIs).
## Key Performance Indicators (KPIs)
- Total Orders: Count of orders placed within a selected time frame.
- Average Delivery Time: Average time taken (in minutes) for order delivery.
- Average Order Value (AOV): Total revenue divided by the number of orders.
- Customer Satisfaction (Rating): Average customer rating (scale of 1 to 5).
- Discount Utilization Rate: Percentage of orders with discounts applied.
## Visualizations (Charts)
- Total Orders Trend: A line chart showing order volume over time (daily/weekly/monthly).
- Delivery Time Analysis: A bar chart showing average delivery time by city.
- Top Restaurants: A horizontal bar chart showing top 10 restaurants based on revenue.
- Customer Ratings Distribution: A pie chart or bar chart showing the breakdown of ratings (1 to 5).
- Cuisine Popularity: A bar chart showing the most popular cuisines based on order count.
## Filters
- Date Range: Filter orders, reviews, and revenue by specific date ranges.
- City/Location: Filter data based on customer or restaurant locations.
- Cuisine Type: Filter data by selected cuisines (e.g., Indian, Chinese, Italian).
- Rating Range: Filter restaurants or reviews based on ratings (e.g., 3 stars and above).
- Discount Applied: Toggle to view only discounted or non-discounted orders.
## Data Sources
- Orders Dataset: Contains details such as Order ID, Customer Name, Location, Restaurant Name, Cuisine, Order Date, Delivery Time, Order Amount, etc.
- Restaurant Dataset: Includes Restaurant Name, Location, Ratings, Reviews, and Cuisine.
- Reviews Dataset: Includes Review Text, Ratings, Review Date, and Customer Feedback.
## Functional Requirements
-Total Orders KPI – Displays the total number of orders placed within the selected period. It requires the Order_ID column to count the number of orders.
-Average Delivery Time KPI – Shows the average time taken for deliveries. It utilizes the Delivery_Time_Minutes and Order_ID columns to calculate the mean delivery duration.
-Average Order Value KPI – Computes the average monetary value of all orders. The Order_Amount and Order_ID columns are used to determine the average order value.
-Customer Satisfaction KPI – Displays the average rating given by customers. It uses the Rating and Review_Date columns to calculate and present customer satisfaction scores.
-Discount Utilization KPI – Represents the percentage of orders where a discount was applied. It uses the Is_Discount_Applied and Order_ID columns to measure discount usage.
-Total Orders Trend Chart – A line chart illustrating order trends over time. It relies on Order_Date, Order_ID, and Customer_Location to display order patterns across different periods.
-Delivery Time Chart – A bar chart analyzing delivery time variations by city. It leverages Delivery_Time_Minutes and Customer_Location to compare average delivery durations.
-Top Restaurants Chart – A bar chart highlighting the top 10 restaurants based on revenue. It utilizes Restaurant_Name, Order_Amount, and Restaurant_Location to rank restaurants by total earnings.
-Ratings Distribution Chart – A pie chart showcasing the distribution of customer ratings. It requires Rating and Order_ID to visualize rating frequencies.
-Cuisine Popularity Chart – A bar chart displaying the most popular cuisines based on order volume. It uses the Cuisine and Order_ID columns to determine which cuisines are most frequently ordered.
## Non-Functional Requirements
- Performance: Dashboards should load within 5 seconds for datasets under 50,000 rows.
- Usability: Intuitive layout for non-technical users.
- Scalability: Ability to handle data growth up to 1 million rows.
## Stakeholders
- Business Analysts: Analyze performance metrics.
- Operations Team: Monitor delivery efficiency.
- Marketing Team: Understand customer preferences and trends.
- Restaurant Owners: Track performance and customer feedback.
