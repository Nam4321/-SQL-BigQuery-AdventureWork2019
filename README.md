# I. Introduction
This project contains an Adventure Works 2019 dataset that I will explore using SQL on Google BigQuery. I was given task to find answers for the following questions related to Adventure Works database.

# II. Exploring the Dataset
In this project, I will write 08 query in Bigquery base on Adventureworks2019

# Query 01: Calc Quantity of items, Sales value & Order quantity by each Subcategory in L12M
### SQL code
![Code 1](https://github.com/Nam4321/-SQL-BigQuery-Bicycle-Manufacturer/assets/80372192/2b301e27-d004-43f8-9a2e-51962473cf1d)
### Query results
![KQ 1](https://github.com/Nam4321/-SQL-BigQuery-Bicycle-Manufacturer/assets/80372192/80532864-efb6-4fb3-ae6e-e8917a69b97e)

# Query 02: Calc % YoY growth rate by SubCategory & release top 3 cat with highest grow rate. Can use metric: quantity_item. Round results to 2 decimal
### SQL code
![Code 2](https://github.com/Nam4321/-SQL-BigQuery-Bicycle-Manufacturer/assets/80372192/f0b92a61-41ad-4863-8116-6c497d962e6d)
### Query results
![KQ 2](https://github.com/Nam4321/-SQL-BigQuery-Bicycle-Manufacturer/assets/80372192/774f8d64-acd3-4e0f-bec8-91040352a900)

# Query 03: Ranking Top 3 TeritoryID with biggest Order quantity of every year. If there's TerritoryID with same quantity in a year, do not skip the rank number
### SQL code
![Code 3](https://github.com/Nam4321/-SQL-BigQuery-Bicycle-Manufacturer/assets/80372192/c3935ed7-5afe-4bd6-81c6-dc9856161251)
### Query results
![KQ 3](https://github.com/Nam4321/-SQL-BigQuery-Bicycle-Manufacturer/assets/80372192/9fc57620-ea82-4248-a0d2-34fc9638436b)

# Query 04: Calc Total Discount Cost belongs to Seasonal Discount for each SubCategory
### SQL code
![Code 4](https://github.com/Nam4321/-SQL-BigQuery-Bicycle-Manufacturer/assets/80372192/d1c1297c-afb3-4a3d-873e-cc89ac109dd8)
### Query results
![KQ 4](https://github.com/Nam4321/-SQL-BigQuery-Bicycle-Manufacturer/assets/80372192/d4ed7be7-63d6-41a2-a3c4-c3db7862723d)

# Query 05: Retention rate of Customer in 2014 with status of Successfully Shipped (Cohort Analysis)
### SQL code
![Code 5](https://github.com/Nam4321/-SQL-BigQuery-Bicycle-Manufacturer/assets/80372192/4cf34250-4cfb-4a2e-ab21-423f4edf1146)
### Query results
![KQ 5](https://github.com/Nam4321/-SQL-BigQuery-Bicycle-Manufacturer/assets/80372192/2c22b27e-9706-44b4-acba-874477602e01)

# Query 06: Trend of Stock level & MoM diff % by all product in 2011. If %gr rate is null then 0. Round to 1 decimal
### SQL code
![Code 6](https://github.com/Nam4321/-SQL-BigQuery-Bicycle-Manufacturer/assets/80372192/478e744b-5a32-4e04-9399-a7a3d6962060
### Query results
![KQ 6](https://github.com/Nam4321/-SQL-BigQuery-Bicycle-Manufacturer/assets/80372192/10efcbdc-2288-4033-88d3-33819d9b9511)

# Query 07: Calc MoM Ratio of Stock / Sales in 2011 by product name
### SQL code
![Code 7](https://github.com/Nam4321/-SQL-BigQuery-Bicycle-Manufacturer/assets/80372192/591e237a-3ed3-4fcc-b681-1032862c473c)
### Query results
![KQ 7](https://github.com/Nam4321/-SQL-BigQuery-Bicycle-Manufacturer/assets/80372192/bc12ffc6-37ba-4273-9f47-091c7da2b80f)

# Query 08: No of order and value at Pending status in 2014
### SQL code
![Code 8](https://github.com/Nam4321/-SQL-BigQuery-Bicycle-Manufacturer/assets/80372192/f11125db-82e6-448b-bfc0-fcd9ee49cb68)
### Query results
![KQ 8](https://github.com/Nam4321/-SQL-BigQuery-Bicycle-Manufacturer/assets/80372192/424c5981-b8ea-46c9-ab30-409523347a96)


# III. Conclusion
In conclusion, my exploration of the Adventureworks2019 dataset using SQL on Google BigQuery based on the Adventureworks2019 dataset has revealed several interesting insights. By exploring Adventureworks2019 dataset, I have gained valuable information about Quantity of items, Sales value & Order quantity,.... which could inform future business decisions. To deep dive into the insights and key trends, the next step will visualize the data with some software like Power BI,Tableau,... Overall, this project has demonstrated the power of using SQL and big data tools like Google BigQuery to gain insights into large datasets.
