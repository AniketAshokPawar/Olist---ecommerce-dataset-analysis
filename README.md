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

## Numerical findings and analysis:

### Overall order trend
![image](https://github.com/user-attachments/assets/ecd21f77-1ee5-4086-8dd2-fead73e1ad89)

## Order trend analysis
### Key findings
![image](https://github.com/user-attachments/assets/57660185-295b-433c-a7d4-7b167787b1e7)

### Orders by Quarter 
![image](https://github.com/user-attachments/assets/311f7af9-cb9f-4cfa-8b98-e110cac7f2a9)

### Key findings
![image](https://github.com/user-attachments/assets/b8986cc5-3107-4ebb-bb91-45f85981eda5)

### Orders by Month
![image](https://github.com/user-attachments/assets/a6c0bf35-60c2-494f-8a49-fde52a2d12a8)

### Key findings
![image](https://github.com/user-attachments/assets/0811591d-8747-4baf-a12d-0befab94f12f)

### Orders by Day of week
![image](https://github.com/user-attachments/assets/1d6be8e2-bdda-4849-ac30-d0e6e0714757)

### Key findings
![image](https://github.com/user-attachments/assets/b57a5027-3dfe-4584-9a8f-ba12adc9a203)

### Orders by time of day
![image](https://github.com/user-attachments/assets/48990240-1c8f-4592-bcab-481d6895ea2f)

### Key findings
![image](https://github.com/user-attachments/assets/5825cf7a-d402-4da9-a6cf-44ce23287ada)

### Conclusion
![image](https://github.com/user-attachments/assets/eb70e437-ede3-41c3-a1f8-8e19d336a425)


## Customer behaviour & regional analysis
### Orders by Payment type
![image](https://github.com/user-attachments/assets/78e3e295-18aa-491d-8320-85f12b25d6d6)

### Key findings
![image](https://github.com/user-attachments/assets/0b2f7563-f44d-4414-9b37-fcccb604df04)

### Review score distribution by Order status
![image](https://github.com/user-attachments/assets/3da6d553-9c03-481c-b700-e6d752b20138)

### Key findings
![image](https://github.com/user-attachments/assets/1412fcb9-ea73-47a2-a527-11356e8e334e)

### Top 5 city by Order count
![image](https://github.com/user-attachments/assets/64c3e588-6ad5-4a28-8ebc-0fecbf10553f)

### Key findings
![image](https://github.com/user-attachments/assets/622ded61-7778-484b-887b-0c915a8f5588)

### Conclusion
![image](https://github.com/user-attachments/assets/e4c54987-b9a9-467d-b921-991296d02ef1)


## Product performance evaluation
### Top 10 product category by Order count, Highly rated, least rated product category
![image](https://github.com/user-attachments/assets/0798e6ef-2241-4090-8255-c47a2d7fa3b0)

### Key findings
![image](https://github.com/user-attachments/assets/0c2c55da-2f72-4c35-a3f6-5b4ca3072b42)

### Conclusion
![image](https://github.com/user-attachments/assets/0567c38e-548a-4d41-8609-8b6093e57ac2)

## Delivery & logistics efficiency
### Top 5 Customer states by Highest average delivery time
![image](https://github.com/user-attachments/assets/15abd7bf-64dd-4469-afc7-3b28326a7518)

### Key findings
![image](https://github.com/user-attachments/assets/dfd649df-fd65-4aa9-bd36-abcefc3f6cfe)

### Top 5 Seller states by Highest average delivery time
![image](https://github.com/user-attachments/assets/58c66586-4493-4864-a700-a974ab14caba)

### Key findings
![image](https://github.com/user-attachments/assets/391bf44b-3a70-40e7-a1ea-82bbde2c97bd)

### Top 5 prdoduct categories by highest delivery time
![image](https://github.com/user-attachments/assets/a323062c-c747-440f-b880-8019028b0e78)

### Percentage of delivery status
![image](https://github.com/user-attachments/assets/6ec804e8-6625-4211-8ba0-661513622847)

### Conclusion
![image](https://github.com/user-attachments/assets/dd661db6-2a07-4635-9f4f-e89332491c5c)

## DASHBOARD
![image](https://github.com/user-attachments/assets/1fe7021d-7d66-42b7-95bf-d53a744d23a5)
