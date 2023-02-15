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

![Annotation 2023-02-15 162117](https://user-images.githubusercontent.com/119788228/219070925-5a957e17-0e5b-4f3e-a13e-87f5383b37e3.png)

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

![Annotation 2023-01-19 ](https://user-images.githubusercontent.com/119788228/219071860-1053245d-47ce-495e-8544-9a44a1f8187b.png)

The highest layoff was experienced in 2022, and the least layoff was in 2021. This was visualized by selecting a doughnut chart from the "Insert tab: Recommended chart ribbon." I selected a pie chart because the category was between 2 and 4 values.

![Annotation 2023-](https://user-images.githubusercontent.com/119788228/219072362-09dae53e-b636-4c4d-b745-f41a15969af7.png)

**The companies that laid off their staff (by company):**

The top 5 companies with the most layoffs between 2020 and 2022 were Meta, Amazon, Uber, Booking.com, and Cisco. Meta had 11,000 layoffs, or about 4.4% of all layoffs, while Amazon and Uber laid off 10,000 and 7,585 staff, respectively.

![Annotation 2023-01-19 161514](https://user-images.githubusercontent.com/119788228/219072833-795c9ee7-69f9-44fc-845d-ff416a2cea2c.png)

I filtered and sorted the data to get the top 5 layoff companies.

![Annotation 2023-01-19 161617](https://user-images.githubusercontent.com/119788228/219073067-a208abcb-99b3-497d-b94d-17d4ded47fe3.png)

This was visualized by selecting a bar chart from the “Insert tab: Recommended chart ribbon."

![Annotation 2023-01-23 142228](https://user-images.githubusercontent.com/119788228/219073539-254bdc34-a447-48f1-bbce-3b5147a99bf3.png)

**The company with the highest fundraising:**

The top 5 most funded companies between 2020 and 2022 were Netflix, Uber, WeWork, Bytedance, and Meta. Netflix got approximately $490,000 in funding, about 34% of the funds raised from 2020 to 2022, while Meta, which had the highest layoffs, was the fifth-most-funded company within that period.

![Annotation 2023-01-19 170714](https://user-images.githubusercontent.com/119788228/219074288-0bea793f-6a1c-4872-bf1a-7acd37b8e97f.png)

![Annotation 2023-01-19 152532](https://user-images.githubusercontent.com/119788228/219074453-10434efa-b19e-4612-a445-976b63168a37.png)

**The stage with the highest fundraise and layoff:**

The companies at the IPO funding stage laid off the most and also got the highest fundraised. They laid off approximately 98,152 employees between 2020 and 2022 and were able to secure funding of approximately $886,364 billion, or about 62% of the total funds raised within that period.

![Annotation 2023-01-19 165237](https://user-images.githubusercontent.com/119788228/219076372-73d9c57a-30ff-4e77-8388-e0a4b8f1745f.png)

![Annotation 2023-01-19 151441](https://user-images.githubusercontent.com/119788228/219077315-b5a9db79-b921-4f25-aad5-2c8be3c219e2.png)

### DATA VISUALIZATION

I drew a rough draft of my dashboard template before I began my pivot table analysis, which was followed by its design and formatting on Microsoft Excel.

![100i](https://user-images.githubusercontent.com/119788228/219081562-809e2d89-8084-4fe8-b12f-f646b4700287.png)

All the data can be visualized at a single glance on this dashboard. Comments and recommendations from experts would be appreciated, thank you.

![Annotation 2023-01-23 141934](https://user-images.githubusercontent.com/119788228/219079520-9647f5f2-b340-4549-a368-f6da6c4d3f56.png)
















