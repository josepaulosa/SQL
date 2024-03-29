# SQL
- - - 
> The jupyter notebook intends to show **how to write** some important **SQL queries** and **statements** for **retrieving data from a database** and **performing actions on a database** - such as: 
> - Creating a **primary key**
> - **Convert varchar datatype to date datatype**
> - **Delete records**, in both tables, that only create noise like the ones regarding missing data and the ones that are out of range
> - Discover the correlation between the day of the week and the number of accidents and visualize data using **Matplotlib**
> - Find the proportion of accidents that took place in urban and rural areas
> - Count the number of accidents by level of severity and data visualization using Matplotlib
> - Retrive the total number of accidents by vehicle type and sort in descending order of number of accidents
> - Compute the number of accidents by accident severity and vehicle type; create a column named 'assessement', in case of the of number of accidents was less than 10 output 'not bad'; if it was equal or greater than 10 and less then 100 output 'could be worse'; lastly if it was greater then 100 output 'terrible' (use of **CASE** and **JOIN**)
> - Find the percentage of accidents by level of severity
> - At what time (hour) most accidents happened by day of the week. Output the days of the week, the hour and the number of accidents (use of the **window function RANK**)
> - Find the days of the week with more casualties than the average across all days of the week (use of the **WITH** and **JOIN** clauses and the SUM and AVG **aggregate functions**)
> - Calculate the quarter-over-quarter percentage change in casualties, rounded to the 2nd decimal point (use of the **window function LAG** and the SUM **aggregate function**)
> - Identify the three days with most casualties by quarter. Output the quarter, the day and the number of casualties (use of the **window function RANK** and the SUM **aggregate function**)
- - - 
- **Note**: I used Aliases several times mainly to improve quickness and readability
- - - 
- The RDBMS used was: **MariaDB**
- - - - 
- You can find the 2 **datasets** regarding Road Safety Data 2020 in UK with which I created a **database** with **2 tables** [here](https://data.gov.uk/dataset/cb7ae6f0-4be6-4935-9277-47e5ce24a11f/road-safety-data)
