\# SQL QA E-Commerce Project



\## Overview



This project was created to practice SQL, database validation, and QA testing techniques using a simulated e-commerce application.



The project focuses on how a QA Engineer can validate data stored in a database after actions performed in the application, such as creating users, placing orders, and processing payments.



\---



\## Project Objectives



\- Practice SQL queries used in QA testing

\- Learn database validation techniques

\- Simulate real-world testing scenarios

\- Verify data integrity between related tables

\- Build a portfolio project for QA Automation and Software Testing roles



\---



\## Database Structure



The database contains the following tables:



\### Users



Stores customer information.



| Column | Description |

|---------|-------------|

| user\_id | Unique user identifier |

| first\_name | Customer first name |

| last\_name | Customer last name |

| email | Customer email |

| registration\_date | Account creation date |



\### Products



Stores product information.



| Column | Description |

|---------|-------------|

| product\_id | Unique product identifier |

| product\_name | Product name |

| price | Product price |

| stock\_quantity | Available stock |



\### Orders



Stores customer orders.



| Column | Description |

|---------|-------------|

| order\_id | Unique order identifier |

| user\_id | Customer who placed the order |

| order\_date | Date of order |

| order\_status | Order status |



\### Order Items



Stores products associated with each order.



| Column | Description |

|---------|-------------|

| order\_item\_id | Unique order item identifier |

| order\_id | Related order |

| product\_id | Ordered product |

| quantity | Quantity ordered |

| item\_price | Product price at purchase time |



\### Payments



Stores payment information.



| Column | Description |

|---------|-------------|

| payment\_id | Unique payment identifier |

| order\_id | Related order |

| payment\_date | Payment date |

| amount | Payment amount |

| payment\_status | Payment status |



\---



\## QA Validation Scenarios



This project will include validation scenarios such as:



\- Verify user creation

\- Verify order creation

\- Verify payment status

\- Verify order totals

\- Verify stock updates

\- Verify completed and failed payments

\- Verify data consistency across tables



\---



\## SQL Topics Covered



\- CREATE TABLE

\- INSERT INTO

\- SELECT

\- WHERE

\- ORDER BY

\- COUNT

\- SUM

\- GROUP BY

\- INNER JOIN

\- LEFT JOIN



\---



\## Technologies Used



\- SQLite

\- DB Browser for SQLite

\- Git

\- GitHub



\---



\## Project Status



🚧 In Progress



Current Progress:



\- \[x] Repository Created

\- \[x] Database Schema Created

\- \[x] Sample Data Started

\- \[ ] SQL Validation Queries

\- \[ ] JOIN Queries

\- \[ ] Reporting Queries

\- \[ ] QA Test Scenarios

\- \[ ] Final Documentation



\---



\## Author



\*\*Bogdan Cristian Pop\*\*



QA Engineer | Test Automation Enthusiast | SQL Learning Project

