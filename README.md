## MICROSOFT EXCEL PROJECT — COMPANY LAYOFFS

This is my first project since I started my data analysis journey, and this was done using Microsoft Excel. I browsed the Kaggle website and came across the dataset on layoffs. I wouldn’t have considered working on this as my project if Meta’s recent layoff due to the slowdown in the economy hadn’t happened.

### ABOUT THE DATASET

The dataset is a CSV file obtained from Kaggle (https://www.kaggle.com/datasets/swaptr/layoffs-2022) and includes layoffs of employees across various industries from COVID-19 to the present. The dataset consists of 9 columns: company (name of the company), location (location of the layoff), industry (industry of the company), total laid off (number of employees laid off), percentage laid off (percentage of employees laid off), date (date of the layoff), stage (stage of funding), country, and funds raised (funds raised by the company).

![1](https://user-images.githubusercontent.com/119788228/218265828-e9baba3b-52a3-4ce0-acfe-9d7079d284f2.png)  
 *The raw dataset before data cleaning occurred*

### DATA CLEANING PROCESS

It is important to clean the data before analyzing it because it may contain unwanted entries, which can cause errors in your analysis.

I started data cleaning by changing the data type of the percentage-layoff column from decimal to percentage.

To calculate the “total number of staff before the layoff occurred,” I added a new column. I also added an IF statement to turn all empty cells into 0 before rounding the values.

I inserted another column to calculate the “total number of staff after the layoff” to get an estimate of how many employees were still employed.

!image

I extracted the year and month from the date column.

I changed the data type of funds raised from general to currency.

Finally, I removed all duplicated values from the dataset.

I turned the dataset into a table format, which was then summarized into a pivot table.

![5](https://user-images.githubusercontent.com/119788228/218265904-4b54ef94-63a7-45a4-a692-c6921363e1f5.png)  
*The clean data set ready to be analyzed*

![6](https://user-images.githubusercontent.com/119788228/218265920-cff57327-161c-4338-a930-10768b9f7f28.png)  

### DATA ANALYSIS

I conducted analysis on the dataset after converting my table into a pivot table, and I was able to provide answers to some of the following questions:

- The total layoff between 2020–2022
- The layoff by Month
- The companies that laid off their staff
- The company with the highest fundraise
- The stage with the highest fundraise and layoff
- The industry with the highest fundraise

**The total layoff between 2020–2022:**

This was represented as "Total layoff by year" on the dashboard, and the pivot table shows the following: I inserted the year column into the row tab and inserted the "total laid off" column into the value tab (this sums up the values automatically).










