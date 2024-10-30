**Northwind Insights Analysis**
----
In this project, I performed an analysis by utilizing SQL to predict various business insights for Northwind, a manufacturer specializing in packaged foods. 
The analysis aimed to provide the management with data-driven answers to their questions regarding customer behavior and overall operations. 

Here are some questions we need to solve: 
  1. What is the total revenue amount for the second half of 1997 (January 1st 1997 to June 30th 1997)? (Discount is on a percentage basis, e.g. 0.15 means 15% off)
  2. What are the top 5 product that got ordered the most in the Beverages category? Show the product name and the number of orders.
  3. What are the top 5 product category that are sold with the highest discount on average? (Using simple average would be fine)
  4. Northwind wants to learn a bit more about how popular each supplier's goods are. They plan to learn about how much volume of each supplier's goods were sold to determine the future negotiations with them about pricing. They have classified the popularity of the supplier's goods as such:
--a. If the total order quantity of the supplier's goods is more than or equal to 3000, the supplier would be classified as 'Highly Popular'. 
--b. If the total order quantity of the supplier's goods is more than 1500 but less than 3000, the supplier would be classified as 'Adequately Popular'. 
--c. If the total order quantity of the supplier's goods is less than or equal to 1500, the supplier would be classified as 'Not Popular'. 
Please create a view that shows the average sales revenue for each popularity classification.
  5. What is the top 3 most popular product category in the country that contributes to the most amount of revenue?
  6. Who is the customer that orders the most from Northwind? How much revenue they contributed?
  7. For the same customer from the last question, please create a view that shows the 3-month moving average total amount under each product category.
  8. For the same customer, what proportion of revenue does the customer contribute to the total revenue in each product category?
