# Super Store Activity Analysis

## Table of Content
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Visualization](#visualization)
- [Results and Findings](#results-and-findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)

## Project Overview

This data analysis project aims to provide insight into the sales and delivery of a super store company over the past 4 years. By analyzing various aspects of the sales and delivery data, we seek to uncover trends, make data-driven recommendations, and gain a deper understanding of the company's performance.

### Data Sources

Sales & Delivery data: The primary data set used for this analysis is the [Super Store Sales Dataset](https://www.kaggle.com/datasets/laibaanwer/superstore-sales-dataset/), containing detailed information about each sale made by the company.

### Tools

- Excel - Data Cleaning.
- Excel - Creating Visuals/Reports.

### Data Cleaning and Preparation

The following tasks were performed in the initial data preparation phase:
1. Data loading and inspection.
2. Handling missing values.
3. Data cleaning and formating.

### Exploratory Data Analysis

EDA involved exploring the sales data to answer key questions, such as;

- What is the average delivery time for each shipping mode?

 ![Bar plot 1](https://github.com/CynthiaTombari/Excel-Project-1/assets/148295544/26a80285-ec7e-4843-9776-63156b3c6b21)

- What is the total profit for each year?

 ![Bar plot 2](https://github.com/CynthiaTombari/Excel-Project-1/assets/148295544/43be0c50-671d-472d-a8bc-53ba806aabe5)

- What are the top 10 countries with the most sale?

 ![Bar plot 3](https://github.com/CynthiaTombari/Excel-Project-1/assets/148295544/67f52c48-0317-4168-ad83-9a0e7536a379)

- What are the top 10 most purchased product sub-category?

 ![Bar plot 4](https://github.com/CynthiaTombari/Excel-Project-1/assets/148295544/44cd8de8-fed5-4fa7-b87b-b5f842050e25)

- What ship mode is most used by customers?

 ![Bar plot 5](https://github.com/CynthiaTombari/Excel-Project-1/assets/148295544/1896d8f0-f4c2-46c1-8b69-06e8b646f22d)

- What product has most sales each year?

 ![Bar plot 6](https://github.com/CynthiaTombari/Excel-Project-1/assets/148295544/71a56c83-2c2b-41fc-96c7-5eff66088d5a)

- What are the average shipping cost by product category?

 ![Bar plot 7](https://github.com/CynthiaTombari/Excel-Project-1/assets/148295544/7eb40a76-a1ac-476d-b400-38bede70e1d4)

- What quantity of products are bought by customers for each category?

 ![Bar plot 8](https://github.com/CynthiaTombari/Excel-Project-1/assets/148295544/80d40be3-e2fe-4139-8c7a-07ede339d635)


### Data Analysis
  - Used the SUMIFS function to find the total profit for each product category for each year.
  - Used the TEXT function to determine the month which highest profit was recorded.

### Visualization


 ![Dashboard](https://github.com/CynthiaTombari/Excel-Project-1/assets/148295544/5c6d2b21-89f3-4373-a46c-83539a21eff3)

### Results and Findings

  The analysis results are summerised as follows:
  1. The company's sales have been steadily increasing over the past 4 years, with highest sales recoreded during the holiday seasons.
  2. Office Supplies is the best perfoming category based on sales quantity.
  3. The Technology category surpasses other categories in terms of sales and revenue.
  4. The Standard Class is by far the most preferred shipping mode by customers, despite having an average delivery time of 5 days.
 
### Recommendations

  Based on the Analysis, we recommend the following actions:
  - Invest in marketing and promotions during peak sales seasons to maximize revenue.
  - While we focus on expanding the Technology category, promotional and marketing stratagies should be implemented to boost low return categories.
  - Despite having the best performing category based on sales quantity, the Office Supplies has the least sales & profit return, hence structured & targeted marketing plans should be setup for this purpose.
  - The total sales each year is way higher than the total profit per year, we recommend an increase in cost per unit as well as delivery cost.
 
### Limitations

  I had to extract the duration from the order_date and ship_date to show the transit duration for delivery, as well as the months to determine peak sales months.
  
  

