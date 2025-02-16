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
Total Orders KPI – Displays the total number of orders placed within the selected period.

    Required Columns: Order_ID

Average Delivery Time KPI – Shows the average time taken for deliveries.

    Required Columns: Delivery_Time_Minutes, Order_ID

Average Order Value KPI – Computes the average monetary value of all orders.

    Required Columns: Order_Amount, Order_ID

Customer Satisfaction KPI – Displays the average rating given by customers.

    Required Columns: Rating, Review_Date

Discount Utilization KPI – Represents the percentage of orders where a discount was applied.

    Required Columns: Is_Discount_Applied, Order_ID

Total Orders Trend Chart – A line chart illustrating order trends over time.

    Required Columns: Order_Date, Order_ID, Customer_Location

Delivery Time Chart – A bar chart analyzing delivery time variations by city.

    Required Columns: Delivery_Time_Minutes, Customer_Location

Top Restaurants Chart – A bar chart highlighting the top 10 restaurants based on revenue.

    Required Columns: Restaurant_Name, Order_Amount, Restaurant_Location

Ratings Distribution Chart – A pie chart showcasing the distribution of customer ratings.

    Required Columns: Rating, Order_ID

Cuisine Popularity Chart – A bar chart displaying the most popular cuisines based on order volume.

    Required Columns: Cuisine, Order_ID
## Non-Functional Requirements
- Performance: Dashboards should load within 5 seconds for datasets under 50,000 rows.
- Usability: Intuitive layout for non-technical users.
- Scalability: Ability to handle data growth up to 1 million rows.
## Stakeholders
- Business Analysts: Analyze performance metrics.
- Operations Team: Monitor delivery efficiency.
- Marketing Team: Understand customer preferences and trends.
- Restaurant Owners: Track performance and customer feedback.

## Dashboard
![Dashbord image](https://github.com/user-attachments/assets/075fde0b-10ed-4044-add6-d9a849cc389a)

