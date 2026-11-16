**Business question**: Which studios, customers and months drive sales for a movie rental shop, and how is the business trending?

**Tools**: Excel (SUMIF, COUNTIF, XLOOKUP, WEEKDAY, IF, array formulas, Pivot Tables, conditional formatting) · Course case study, AnalytixLabs

**Data**

Five linked sheets: Customer (554 customers), Rental Transaction (3,872 transactions, Jul 2012 to Sep 2014), Rental Transaction Line Item (6,310 rentals), Movie (307 titles), plus the question sheets.

**What I did**
Completed missing columns using SUMIF and COUNTIF (total transactions and total spend per customer), XLOOKUP (movie studio), and WEEKDAY with IF (weekday or weekend tag).
Calculated each customer's DVD share of spend (DVD Movies Total Price ÷ Total Price).
Studio analysis (Q3): Pivot Table of total and average price by studio, with top contributors highlighted.
Customer segmentation (Q4): Tagged customers into four spend bins (0-30, 30-50, 50-80, above 80) and counted customers and transactions in each.
Trend analysis (Q5): Pivot Table of monthly transactions with month-over-month change for every year.
Key findings
Total sales were 34,923 across 3,872 transactions, with an average line price of about 5.53.
Sales are concentrated in a few studios: Warner Brothers leads with 16.9% of total sales, and the top three (Warner Brothers, Fox, Universal) account for about 40%.
Average price per rental is almost flat across studios (roughly 5.1 to 6.6), so studio revenue differences come from volume, not price.
The 50-80 spend bin is the core segment: 232 customers (42%) and 1,637 transactions (42%).
The highest spenders matter most: customers above 80 are 25% of customers but 34% of transactions.
Transactions peaked in Sep 2013 at 493, then fell by 325 in Oct 2013 and stayed far lower afterwards. 2013 alone contributed 65% of all transactions.
Charts

Top studios by sales

Customers and transactions by spend bin

Monthly transactions

**Recommendations**
Prioritise stock and promotions for the top studios.
Reward the above-80 bin with loyalty offers to protect the most valuable customers.
Investigate what drove the autumn 2013 spike and the sharp fall after it (promotion, new release slate or store change) before planning next year's campaigns.
**Files**
The workbook and dataset are course material and are not published here.
screenshots/: charts for the Q3, Q4 and Q5 results

<img width="1146" height="475" alt="Q5- MoM_Change" src="https://github.com/user-attachments/assets/781ba31d-9711-47e9-b5dd-3f58cd17e7e5" />
<img width="1009" height="409" alt="Q4-Spend_bins" src="https://github.com/user-attachments/assets/81e5047c-530c-4827-b0f2-f52b7d33e354" />
<img width="1058" height="411" alt="Q3-Studio_Sales" src="https://github.com/user-attachments/assets/ad8be9b2-c4fb-424a-9982-de5a2ba4c673" />

**About me**

Saranya Pillai, ECE engineer (M.Sc., Hochschule Darmstadt) moving into data analytics. [LinkedIn URL - https://www.linkedin.com/in/saranya-pillai-18235b4b/]
