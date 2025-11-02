# Supermarket-Sales
This repository contains the results of analysis and visualization of supermarket transaction data in Myanmar from January to March 2019. The data was obtained from the Kaggle website: https://www.kaggle.com/datasets/faresashraf1001/supermarket-sales?select=SuperMarket%20Analysis.csv.

## Data Preparation

### Change Data Type
![image alt](https://github.com/jokoGemblonG/Supermarket-Sales/blob/e4d93054a2d037c7e7b0f03a5eea5b6a1acb8e58/Photos/data_type_1.png)

by using the code above, the **Date** column type has been converted to datetime type

### Add Revenue Column
![image alt](https://github.com/jokoGemblonG/Supermarket-Sales/blob/0594217b22ea0325a479abfef8a6bffe2dc361d4/Photos/add_revenue_column.png)

### Check and Fix Typing Problem

![image alt](https://github.com/jokoGemblonG/Supermarket-Sales/blob/5ece26d1fcb3720cfeded10fd616a33003fc5432/Photos/typing_check.png)

The output shows that only **Gender** column that has a typo. So we have to fix this problem.

![image alt](https://github.com/jokoGemblonG/Supermarket-Sales/blob/5ece26d1fcb3720cfeded10fd616a33003fc5432/Photos/solving_the_typing_problem.png)

After fixing the typing problem, we should check if there is a **duplicate data**

![image alt](https://github.com/jokoGemblonG/Supermarket-Sales/blob/969c07976e105cd8511950b018cc5683aa44f7cc/Photos/duplicate_check.png)

There is no duplicate data. Data Preparation is finish, then we could proceed the **Exploratory Data Analysis**.

## Exploratory Data Analysis

### Company Revenue

![image alt](https://github.com/jokoGemblonG/Supermarket-Sales/blob/8d19ec6df91df665515f8ae8bf72b4cd04268752/Photos/total%20revenue%20by%20week.png)

We can conclude an information from the graph that the highest company revenue was achieved on Week 4 (21-27 January 2019), amounting to $27.892,27 and the lowest company revenue was achieve on Week 8 (18-24 February 2019), amounting to $16.503,49.
The highest company revenue in a day was achieved on March 15, 2019, amounting to $7.118,14 and the lowest company revenue in a day was achieve on February 13, 2019, amounting to $889,75.

#### Company Revenue in Each City

![image alt](Photos/Cumulative Revenue by City.png)

