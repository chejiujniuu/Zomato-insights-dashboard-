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
View Name
Description
Required Columns
Total Orders KPI
Displays total orders placed within the selected period.
Order_ID
Average Delivery Time KPI
Shows the average delivery time for orders.
Delivery_Time_Minutes, Order_ID
Average Order Value KPI
Calculates the average value of all orders.
Order_Amount, Order_ID
Customer Satisfaction KPI
Displays the average rating given by customers.
Rating, Review_Date
Discount Utilization KPI
Shows the percentage of orders with discounts applied.
Is_Discount_Applied, Order_ID
Total Orders Trend Chart
Line chart showing order trends over time.
Order_Date, Order_ID, Customer_Location
Delivery Time Chart
Bar chart analyzing delivery time by city.
Delivery_Time_Minutes, Customer_Location
Top Restaurants Chart
Bar chart showing the top 10 restaurants by revenue.
Restaurant_Name, Order_Amount, Restaurant_Location
Ratings Distribution Chart
Pie chart showing distribution of customer ratings.
Rating, Order_ID
Cuisine Popularity Chart
Bar chart highlighting the most popular cuisines.
Cuisine, Order_ID
## Non-Functional Requirements
- Performance: Dashboards should load within 5 seconds for datasets under 50,000 rows.
- Usability: Intuitive layout for non-technical users.
- Scalability: Ability to handle data growth up to 1 million rows.
## Stakeholders
- Business Analysts: Analyze performance metrics.
- Operations Team: Monitor delivery efficiency.
- Marketing Team: Understand customer preferences and trends.
- Restaurant Owners: Track performance and customer feedback.
