# README for Assignment 2 <br>

## Database Schema 
The database schema used in the assignment is as follows:<br>
## Part 
•P# (Part Number)<br>
•PName (Part Name)<br>
•Producer<br>
•Year<br>
•Price<br>
## Customer
•C# (Customer Number)<br>
•CName (Customer Name)<br>
•City<br>
## Supply
•S# (Supply Number)<br>
•P# (Part Number)<br>
•C# (Customer Number)<br>
•Quantity<br>
•Amount<br>
•Date (Supply Date)<br>
<br>
Note that Dates are expressed in the format YYYY-MM-DD.<br>

## Queries <br>
Each query is expressed in relational algebra, relational calculus, and SQL.

## Relational Algebra & Relational Calculus Queries <br>
1-List names and cities of all the customers.  <br>
2-List names and prices of those parts produced by Apple or Samsung in 2020.  <br>
3-List supply dates, quantities, and amounts of all the Apple parts produced in 2020. <br>
4-For each supply with a quantity over 1000 and after 2019-01-01, list the part name, customer name, and customer cities. <br>
5-List names and cities of the customers who bought one or more Apple products. <br>
6-List names and cities of the customers who did not buy any Apple product. <br>
7-List names and cities of the customers who bought Apple products only. <br>
8-List names and cities of the customers who bought all the Apple products. <br>
## SQL Queries  <br>
1-Find the average price of Apple products. <br>
2-For each Apple product, list product number, product name, and total supply quantity since Jan 1, 2019. <br>
3-For each Apple product supplied to Guelph in 2020, list product number, product name, total supply quantity, and total supply amount. <br>
4-For each Apple product supplied to more than 10 different customers in Guelph in 2020, list product number, product name, total supply quantity, and total supply amount. Sort the result by product name. <br>
