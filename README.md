# Product-Analyst-homework
  Joining tables, Aggregation, and Data Analysis
  
## Description
  Example on how to join tables, use aggregate functions to get data, and a data analysis. The examples are in text files all titled respectively. The Joining_Tables and Aggregate text files copmose of queries using the PostgreSQL database. Within the files, there are descriptive details on the statements and queries that were used to emphasize on their purposes. For the Data_Analysis text file, there is a summary of a data analysis and how the data analysis was concluded.
  
## Joining Tables
  For the Joining Tables challenge, I selected the coulmns that the data was going to be derived from and joined the different columns together using an inner join between the three different tables that had some relation. To join the tables together accordingly so I could get the results that I wanted, I had to join the tables at the right columns, mainly to avoid a cartesian product that would have resulted in a lot of information that was not needed. I used the primary keys of the user table and joined them with the user_id column of the loans table, than in order to get the proper information from the transactions table, I joined the primary key of the loans table with the loans_id column in the transactions table. All the information between two joined tables were exactly the same. I then laid some requirements for the select statements using the WHERE clause in oder to get the withdran loans by using the IN command and only getting the loans that were either active or repaid. There was also another requirement to get the transactions that were disbursements so the AND command was used in order to use the WHERE clause in another requirement. Lastly, the ORDER BY clause was used to display the data by 
when the users created their accounts in descending order

## Aggregation
  The first thing that was done was changing the data type of the created column from a (char) data type to a (date) data type in order to specify each month for what data was to be retrieved from the months and the coumn was displayed as month using the AS command. I also used aggregate functions to get values like sums, counts, minimums, maximums, and averages in the select statements. All the data was to come from the loans table and the GROUP BY clause was used with the month column to get all the data from the other columns relevant to the months that were in the table. Lastly, the ORDER BY clause was used to display the data in descending order of the months.
  
## Data Analysis
  Tableau was used as a visual tool to display the different dimensions and measurements from the excel file. I pieced different information together to come up with the best analysis on which group or gategories had the most weekly logins. Trying to find a relationship beteen different factors was applicable to doing the analysis and I looked to narrow the analysis more. It was obvious what dimesnsions had the strongest correlations with weekly logins and from that point on I tried to narrow the results more by finding other factors that may have also had a contribution to the weekly logins.

# Tools
  SQL powershell (psql), pdAdmin 4, and Tableau 2020.2
