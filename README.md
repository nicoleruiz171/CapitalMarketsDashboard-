# Capital Markets Dashboard - Enhanced ETL & AWS Integration
***This project is a dynamic capital markets dashboard that integrates Yahoo Finance and FRED API data, performs ETL (Extract, Transform, Load) processes, and visualizes bond price, returns, volatility, and yield data. It also includes AWS S3 integration to upload the processed data files for cloud storage.***

## How It's Made:
***Tech used:*** Python, Jupyter Notebook, Yahoo Finance API, FRED API, AWS S3, Matplotlib, Pandas, IPython widgets

This project leverages various data sources, including Yahoo Finance for bond price data and the FRED API for historical yield data. The project follows a standard ETL pipeline:

***Extract:*** Data is pulled from Yahoo Finance and FRED API.

***Transform:*** The data is cleaned, with calculations for cumulative returns, volatility, and Sharpe ratio.

***Load:*** Data is visualized with Matplotlib and stored as CSV files, which are then uploaded to AWS S3.

I used Jupyter Notebook to run this code interactively, and IPython widgets allow users to select bonds, input date ranges, and view updated visualizations.

## Optimizations:
Integrated AWS S3 functionality to store large datasets without overwhelming local storage.

## Lessons Learned:
Gained deeper understanding of ETL processes and how to integrate real-time financial data from APIs.

Gained hands-on experience with AWS S3 and managing cloud storage for large datasets.

Learned how to make my data analysis process interactive using Jupyter Notebook widgets, which significantly improved the user experience.

