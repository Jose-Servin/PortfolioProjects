# COVID Data Analysis Project

An drill down overview of COVID data from [Our World in Data](https://ourworldindata.org/covid-deaths) examining various metrics such as percent population infected, mortality rate, 
average infection rate and more. Data was drilled down from Global Numbers to Continents to Indivudual Countries. 

## Description

This project runs various queries on two joined tables. <br>
* Table 1: Covid_Deaths examines covid realted deaths on a day to day basis grouped by Continent, Countries and Global Data. <br>
* Table 2: Covid_Vaccinations examines vaccinations on a day to day basis grouped by Continent, Countries and Global Data. <br>

These two tables were INNER JOINED on both countries and date, queries can be found in the [SQL Data Exploration file](https://github.com/Jose-Servin/PortfolioProjects/blob/main/SQL_Data_Exploration_1).
 <br>
 <br>
Due to the import of a CSV into Postres using pgAdmin, NULL values have been converted to 0 and ISO_codes that represent Global Data are ommited when looking at Country Data to avoid data repetition.
For example, The North America Continent Data represent Greenland, Canada, USA and Mexico aggregated but when looking on an individual Country level, Continent data should be ommited by use of WHERE clause.
<br>
<br>
[The Tableau Tables and dashboard](https://public.tableau.com/app/profile/jose.servin/viz/COVIDDashboard_16309572414230/Dashboard1?publish=yes) were created using Tableau Public. SQL queries can be found [here](https://github.com/Jose-Servin/PortfolioProjects/blob/main/Tableau_Queries). The final presentation focuses
on The United States, The United Kingdom, India, China and Mexico but different selections are possible. 
<br>
<br>
This Data Analysis Project is my first full scale data exploration, aggregation and presentation analysis focusing on COVID data. I chose this topic due to the data availability,
importance and as a way to implement the MySQL and PostreSQL coding knowledge I have gained in the past 4 months. <br>
<br> 
As I continue my studies in Data Analytics using statistics, SQL and Python I'll share new and exciting projects! Thanks & Gig'Em! 

## Getting Started

### Dependencies

* Basic knowledge in SQL.
* Postres and pgAdmin or any equivalent SQL script program. 
* Microsoft Excel
* Tableau Public

### Installing

* Postgres can be downloaded [here](https://www.postgresql.org/).
* pgAdmin can be downloaded [here](https://www.pgadmin.org/download/).
* Tableau Public can be downloaded [here](https://public.tableau.com/en-us/s/).
* REMEMBER: NULL values are transformed to 0 (zero's) and ISO_Codes are ommited when looking at Country data to avoid data repetition. 

### Executing program

* All SQL queries can be ran in pgAdmin or equivalent. 


## Authors
* Jose Servin <br>
Let's connect via
[LinkedIn](https://www.linkedin.com/in/jose-servin-68bb24113/)

## Acknowledgments

This project follows along [Alex The Analyst](https://www.youtube.com/c/AlexTheAnalyst) Data Analysis series on YouTube. <br>
Credits and many thanks for his valuable teachings, important lessons and motivation to continue exploring data!
