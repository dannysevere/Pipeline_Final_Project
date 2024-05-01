# Pipeline_Final_Project
Final Project for my Data Pipeline Engineering course. Exhibition of some of the skills I learned through the semester such as database creation, data ingestion, anomaly handling, querying in SQL Server and Postgres, querying through the use of pandas dataframes and dataframe manipulation with indexing, and for/while loops.

We were tasked with creating a database for a sports betting company and ingesting the data from multiple different sources for all teams in the NFL from 2000-2022. First I planned the database structure in an ERD with Lucidchart and then created a data dictionary in Excel. I iterated through three CSV files: teams, stadiums, and games (details for every game played in each season); I also pulled data from two SQL Server tables for customer data, and the individual bets placed by the 2000 customers on file. 

I wrote code to programmatically clean the data and ensure it followed the database structure for the ease of committing to the database. Any anomalies were handled without breaking the loop or connection and appended to a list to easily fix later. 

In total 130,000+ records were ingested, taking about 12 hours to complete after hitting 'run'. After, I performed a series of queries to ensure data was ingested properly as well as give the company valuable insights about customer value. In total, the project took over 40 hours of continual work.
