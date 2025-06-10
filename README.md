# TECH STOCK PRICES ANALYSIS

## Background
This dataset consists of daily stock prices and trading volumes for ten prominent technology companies. The data is provided in separate CSV files for each company and was sourced from Yahoo Finance. This project aims to explore and analyze this data to identify key trends and insights into the performance of these tech stocks.

## Data Understanding
The dataset for each stock includes the following columns:
| Column | Explaination |
|-|-|
| Date | Date of observation |
| Open | Opening price of the stock |
| High | Highest price during the trading day |
| Low | Lowest price during the trading day |
| Close | Closing price of the stock |
| Adj Close | Adjusted close price, adjusted for splits and dividend distributions |
| Volume | Number of shares traded during the trading day |

## Technologies Used
The technologies used for the project are Python, Pandas (CSV I/O, `to_datetime` conversions, `groupby` aggregations, percentage-change calculations), Matplotlib (Time-series plotting with customized ticks, legends, and annotations). 

## Data Cleaning Process
The data cleaning process involved the following steps:
* Each of the ten CSV files was loaded into a separate pandas DataFrame.
* The 'Date' column in each DataFrame was converted from a string to a datetime object to facilitate time-based analysis. The format was then standardized to 'dd Mon YYYY'

## Findings
  * Identified Amazon (AMZN) as having the highest closing price ($3731.41 on July 8th, 2021) based on the most recent data. 
  * Visualized the closing price at the end of each month for the 10 tech stocks. 
  * Determined NVIDIA (NVDA) experienced the greatest percent increase in closing price (29.81% on November 11th, 2016).

## Conclusion
This project provides a comprehensive analysis of the stock prices of ten leading technology companies. The findings from the EDA and the visualizations offer valuable insights into the performance and volatility of these stocks, which can be useful for investment analysis and market trend studies. The analysis successfully identified key metrics such as the highest closing price and visualized monthly trends to provide a clear understanding of the stocks' performance.
