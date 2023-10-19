# Pizza-Orders-Visualization

### Inspired by Adam Finer's [YouTube video](https://youtu.be/0rB_memC-dA?si=qH-6NqmDfZbj2ucu)
### Data Source: [Learn BI](https://learnbi.online/pizzaproject)

# Business Scenario

Our friend owns a local pizzeria that has been experiencing significant growth lately. To help them manage their business more effectively, they have asked for assistance in creating three dashboards to analyze various aspects of their operations. They have provided data on orders, customers, customer addresses, ingredients, inventory, menu items, recipes, staff rotations, and staff shifts. The three dashboards will provide insights into order activity, inventory management, and staff-related data.

## Dashboard 1 - Order Activity

This dashboard will focus on monitoring the pizzeria's order activity and sales performance.

- Total Orders: A real-time count of the total number of orders received.
- Total Sales: The cumulative revenue generated from all orders.
- Total Items: The total number of individual menu items sold.
- Average Order Value: The average value of each order.
- Sales by Category: A breakdown of sales by different menu item categories (e.g., pizza, pasta, beverages).
- Top Selling Items: A list of the most popular menu items.
- Orders by Hour: A chart showing the distribution of orders by the hour of the day.
- Sales by Hour: A chart displaying sales amounts throughout the day.
- Orders by Address: A map or list showing the locations of customer addresses with the highest order frequency.
- Orders by Delivery/Pickup: A comparison of orders for delivery and pickup.

## Dashboard 2 - Inventory Management

This dashboard will help in managing the pizzeria's inventory efficiently.

- Total Quantity by Ingredient: A list or table displaying the current quantity of each ingredient in stock.
- Total Cost of Ingredients: The sum of the costs of all ingredients in stock.
- Calculated Cost of Pizza: The cost of making a standard pizza, including the ingredient costs.
- Percentage Stock Remaining by Ingredient: A visual representation of how much of each ingredient is left as a percentage.
- List of Ingredients to Re-order: A dynamic list of ingredients that need to be re-ordered based on low inventory levels.

## Dashboard 3 - Staff

This dashboard will focus on staff management and cost analysis.

- Total Staff Cost: The total cost incurred in paying the staff, including wages and benefits.
- Total Hours Worked: The cumulative number of hours worked by all staff.
- Hours Worked by Staff Member: A breakdown of hours worked by each staff member.
- Cost per Staff Member: The cost associated with each individual staff member, considering their wages and hours worked.

These dashboards will provide our friend with comprehensive insights into their pizzeria's operations, enabling them to make informed decisions and further enhance their business's growth. They can use the data to optimize inventory, manage staff efficiently, and tailor their menu items to customer preferences.

## Database Design and Data Setup

1. We began by creating a relational database diagram using [Quick DBD](https://app.quickdatabasediagrams.com/#/d/bMc4bp). This diagram served as a guide for the subsequent table creation in MySQL.

2. The generated diagram was then exported to MySQL, resulting in a SQL query for table creation. You can find the SQL script [here](https://github.com/samekj/Pizza-Orders-Visualization/blob/main/PizzaDB.sql).

3. After creating the database structure, we proceeded to populate the tables with data. We used the Table Data Import Wizard in MySQL Workbench to efficiently fill the tables with the necessary information. Data Source [here](https://learnbi.online/pizzaproject).

## Query Development

4. To prepare the data for visualization, we created specific queries for different aspects of the business:
   - [Orders Query](https://github.com/samekj/Pizzeria-Visualization/blob/main/Queries/orders_query.sql): Query to retrieve information related to customer orders.
   - [Stock Query 1](https://github.com/samekj/Pizzeria-Visualization/blob/main/Queries/stock_query1.sql): Query to manage stock and inventory data.
   - [Stock Query 2](https://github.com/samekj/Pizzeria-Visualization/blob/main/Queries/stock_query2.sql): Another query for inventory management.
   - [Staff Query](https://github.com/samekj/Pizzeria-Visualization/blob/main/Queries/staff_query.sql): Query to gather data on staff and their activities.

## Dashboard Creation

5. Finally, we used [Google Looker](https://lookerstudio.google.com) to create a comprehensive dashboard for the pizzeria. This dashboard integrates the data retrieved from the queries and provides a visual representation of the business's performance.

You can access the complete pizzeria dashboard here: [Pizzeria Dashboard](https://lookerstudio.google.com/reporting/9252b073-89a8-4fb1-b0c8-456544f83cd4).

This documentation outlines the process we followed to set up the database, create queries for data retrieval, and develop a dashboard for the pizzeria using Google Looker.
