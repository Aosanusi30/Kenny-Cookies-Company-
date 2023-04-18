
![](HomePage.JPG)
-----



# Introduction
This data was gotten from Alex YouTube Channel. And it contains four (4) excel sheets. Power BI was used to clean, analyze and visualize the report. The datasets all together are 9 fields and 3k+ records 

***Disclaimer***: *The company 'Kenny Cookies Company' is an imaginary and do not in anyway relates to an actual company.*

# Data Cleaning 
The dataset contains messy data and all year orders from 2017 - 2020 were entered on a separate workbook which makes it four (4) datasets. In order to merge all four datasets together and to allow Power BI automate the cleaning process, a folder was created and named Kenny Cookies and two of the datasets 2017 and 2018 were moved into the folder, and the data was upload into Power BI by using get data from folder. The only disadvantages with these is that the data most have the same structure. After the cleanin, 2019 and 2020 datasets was added and the data refresed and the datasets was cleaned automatically. 

### Cleaning of some column
- company ID and company Name were typed together and needs to be splited. For the Company ID and Company Name to be on a separate column, split by delimiter (space) was used to split the data. The data type were changed to their appropriate data type
- date data type for order date and ship date
- Revenue and cost to currency 
- creating of profit column by subtraction revenue from cost and data type currency. 
- days to ship column was added by substrating ship date from order date.
- days of the week was created for both ship date and order date

After the cleaning, the dataset has 13 fields and 3k+ columns

# Data Modeling 
The dataset consist of one fact table i.e the order table. From the fact table, a dimension table was extracted onto a separate table. 
The fact table consist of 
- OrderId
- CustomerId
- Customer Name 
- Cookies Shipped 
- Order date
- Ship date 
- Revenue
- Cost 
- Profit
- Days to ship
- Days of order 
- Days of ship

The dimension table consist of 
- CustomerId
- Customer Name 

This was done to test my data modeling skils

# Insights 


# Conclusion 


# Recommendation

# Thank you

![](thank-you-2.gif)
