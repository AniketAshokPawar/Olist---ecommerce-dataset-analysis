# OLIST ECOMMERCE DATASET ANALYSIS
## Introduction:
The Olist eCommerce dataset is a collection of data from a Brazilian e-commerce company that connects small to medium-sized retailers with customers across the country.
## Objective: 
*	To identify order trends

*	Customer behaviour & regional analysis

*	Product performance evaluation

*	Delivery and logistics efficiency

## Data overview:
*	Data source: 
The dataset is sourced from Olist, a Brazilian eCommerce platform and It is publicly available on Kaggle platform.

## Data description: 
•	The analysis focuses on following key columns: Order ID (unique order identifier), Customer unique ID (unique customer identifier), Order purchased date and Order delivered date (timestamps for order processing), Payment value (total price including freight), and Review score (customer rating from 1 to 5).

•	Records: [Number of rows - 119143]

•	Features: [Number of columns - 31]

•	Data records date: [ From – 04 sept, 2016]: [Till – 17 oct, 2018]

## Data pre-processing: 
•	Handling Missing Values:
Imputed missing values using median, mode values and calculated imputation based on data distribution.

•	Remove duplicates rows: 
Removed duplicates rows using in-built pandas’ function.

•	Data transformation: 
Converted product category name from Brazilian language to English.

## Methodology:
The analysis was conducted using Python and key libraries such as Pandas for data manipulation, Seaborn and Matplotlib for data visualization, and Microsoft Word for report preparation. Statistical methods including mean, median, mode, and the five-number summary were applied to summarize data and identify key patterns and trends. 
