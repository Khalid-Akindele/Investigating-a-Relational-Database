# Project Details

## **Introduction**
The Sakila DVD Rentals Database is an imaginary dataset that holds information about a company that rents movie DVDs. For this project, I used SQL to query the database to gain an understanding of the customer base, such as what the patterns in movie watching are across different customer groups, how they compare on payment earnings, and how the stores compare in their performances.  The entity relationship diagram (ERD) for the DVD Rental database is provided in the repo.

**Link to Dataset**

` http://www.postgresqltutorial.com/postgresql-sample-database/ `

#

Each of the SQL queries includes an explicit join, making use of CTEs - Common Table Expressions to breakdown the complex queries into easily uderstandable pieces and enhance query performance (runtime, accuracy).

The queries make use of aggregations to answer important questions. Window function is also utilized in one of the queries to increase efficiency and reduce complexity making it easier to analyze partitions of the dataset.

#

## Queries and Questions Answered

**Query 1** - Create a query that lists each movie, the film category it is classified in, and the number of times it has been rented out.

**Question** -   _What is the Sum of Rental Count by Film Category?_

**Query 2** - Can you provide a table with the movie titles and divide them into 4 levels (first_quarter, second_quarter, third_quarter, and final_quarter) based on the quartiles (25%, 50%, 75%) of the average rental duration(in the number of days) for movies across all categories? 
Make sure to also indicate the category that these family-friendly movies fall into.

**Question** - _What is the Average Rental Duration of Films?_

**Query 3** - We would like to know who were our top 10 paying customers, how many payments they made on a monthly basis during 2007, and what was the amount of the monthly payments. 
Can you write a query to capture the customer name, month and year of payment, and total payment amount for each month by these top 10 paying customers?

**Question** - _Who are the Top 10 Paying Customers?_

**Query 4** - Finally, for each of these top 10 paying customers, I would like to find out the difference across their monthly payments during 2007. 
Please go ahead and write a query to compare the payment amounts in each successive month. Repeat this for each of these 10 paying customers. Also, it will be tremendously helpful if you can identify the customer name who paid the most difference in terms of payments.

**Question** - _What is the Maximum Difference in Monthly Payments by the Top 10 Customers?_


_The repo contains the visuals answering the questions asked in each query in the `SQL_Project_Report` file._

The `SQL_Project_Queries` file contains the actual queries used to answer questions in the file.

#
