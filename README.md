# Product-Analyst-homework
  Joining tables, Aggregation, and Data Analysis
  
## Description
  Example on how to join tables, use aggregate functions to get data, and a data analysis. The examples are in text files all titled respectively. The Joining_Tables and Aggregate text files copmose of queries using the PostgreSQL database. Within the files, there are descriptive details on the statements and queries that were used to emphasize on their purposes. For the Data_Analysis text file, there is a summary of a data analysis and how the data analysis was concluded.
  
## Joining Tables
  For the Joining Tables challenge, I selected the coulmns that the data was going to be derived from and joined the different columns together using an inner join between the three different tables that had some relation. To join the tables together accordingly so I could get the results that I wanted, I had to join the tables at the right columns, mainly to avoid a cartesian product that would have resulted in a lot of information that was not needed. I used the primary keys of the user table and joined them with the user_id column of the loans table, than in order to get the proper information from the transactions table, I joined the primary key of the loans table with the loans_id column in the transactions table. All the information between two joined tables were exactly the same. I then laid some requirements for the select statements using the WHERE clause in oder to get the withdran loans by using the IN command and only getting the loans that were either active or repaid. There was also another requirement to get the transactions that were disbursements so the AND command was used in order to use the WHERE clause in another requirement.

# Tools
  SQL powershell (psql), pdAdmin 4, and Tableau 2020.2
