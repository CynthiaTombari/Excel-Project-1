# Super Store Activity Analysis

## Table of Content
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
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
- What is the total profit for each year?
- What are the top 10 countries with the most sale?
- What are the top 10 most purchased product sub-category?
- What ship mode is most used by customers?
- What product has most sales each year?
- What are the average shipping cost by product category?
- What quantity of products are bought by customers for each category?

### Data Analysis
  - Used the SUMIFS function to find the total profit for each product category for each year.
  - Used the TEXT function to determine the month which highest profit was recorded.
 
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
  
  

