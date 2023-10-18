# Pizza-Orders-Visualization

### Data Source: [Learn BI](https://learnbi.online/pizzaproject)

A friend of ours 
The business task is to visualize some data for a local pizzeria. We are provided with 10 csv files:
- orders
- address
- customers
- ingredients
- inventory
- item
- recipe
- rotation
- shift
- staff

With the help of [Quick DBD](https://app.quickdatabasediagrams.com/#/d/bMc4bp) we create a relational database diagram as a guide for the posterior table creation in MySQL. Next, we proceed to export the diagram to MySQL, the resultant [query](https://github.com/samekj/Pizza-Orders-Visualization/blob/main/PizzaDB.sql) creates the empty tables. Finally, we fill our tables using the Table Data Import Wizard in MySQL Workbench.

  
## Dashboard 1 - Order Activity
For this, we will need a dashboard with the following data:
1. Total orders
2. Total sales
3. Total items
4. Average order value
5. Sales by category
6. Top selling items
7. Orders by hour
8. Sales by hour
9. Orders by address
10. Orders by delivery/pickup

## Dashboard 2 - Inventory Management
1. Total quantity by ingredient
2. Total cost of ingredients
3. Calculated cost of pizza
4. Percentage stock remaining by ingredient
5. List of ingredients to re-order based on remaining inventory

## Dashboard 3 - Staff
1. Total staff cost
2. Total hours worked
3. Hours worked by staff member
4. Cost per staff member

[Learn BI](https://learnbi.online/pizzaproject)
[Pizzeria Dashboard](https://lookerstudio.google.com/reporting/9252b073-89a8-4fb1-b0c8-456544f83cd4)

