 ## Task 5: SQL Joins – Customer and Order Analysis ##
Project Description
This SQL project demonstrates how to create and populate relational tables (Customers and Orders) and perform various JOIN operations such as INNER JOIN, LEFT JOIN, RIGHT JOIN, and FULL JOIN (simulated using UNION). The project helps in understanding how to link related data from multiple tables and extract meaningful insights.

# Database Schema
Customers Table
| Column   | Data Type   | Description       |
| -------- | ----------- | ----------------- |
| Cust\_id | INT (PK)    | Customer ID       |
| Name     | VARCHAR(50) | Customer Name     |
| City     | VARCHAR(50) | City of Residence |

 Orders Table
 | Column    | Data Type   | Description               |
| --------- | ----------- | ------------------------- |
| order\_id | INT (PK)    | Order ID                  |
| Cust\_id  | INT (FK)    | Customer ID (foreign key) |
| product   | VARCHAR(50) | Product Name              |
| amount    | INT         | Purchase Amount           |
