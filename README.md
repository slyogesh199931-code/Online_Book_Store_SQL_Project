# Online_Book_Store_SQL_Project
This project is a data analysis system developed using PostgreSQL to manage and analyze an Online Book Store database. It uses a relational database schema with three core tables—Books, Customers, and Orders—containing 500+ records of realistic e-commerce data imported from CSV files.
The primary objective of this project is to solve real-world retail business problems by extracting key performance metrics. 
The analysis is structured into two parts:Basic Data Exploration: Focuses on filtering inventory by genre, tracking publication years, locating customer demographics (e.g., Canada), and monitoring absolute metrics like total revenue and stock levels.
Advanced Business Insights: Utilizes complex SQL techniques like Multi-table JOINS, Aggregate Functions (SUM, AVG, COUNT), Grouping (GROUP BY, HAVING), and Null handling (COALESCE) to unlock deeper analytics.
Key Analytical Insights Achieved:Sales Analytics: Evaluated total books sold per genre and identified the top 10 most frequently ordered books to pinpoint high-demand stock. 
Customer Behavior: Segmented loyal customers with repeat orders and tracked high-value transactions (orders >$30) back to their specific cities.Financial Performance: Calculated the total revenue, identified the highest-spending customers, and analyzed pricing strategies across genres like Fantasy.
Inventory Management: Created a dynamic tracking query using LEFT JOIN and COALESCE to calculate the exact remaining stock for each book after subtracting fulfilled order quantities.
This project effectively demonstrates how relational databases can be utilized to optimize inventory control, understand customer spending habits, and drive data-backed business decisions for an e-commerce platform.
