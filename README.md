# Python-project-for-data-science-IBM-data-science-professional-certificate
Tesla and GameStop revenue dashboards

📊 Tesla & GameStop Stock and Revenue Dashboard

📖 Overview
This project is part of the IBM Data Science Professional Certificate (Final Assignment).
The goal is to analyze the historical stock prices and quarterly revenues of Tesla (TSLA) and GameStop (GME), then visualize them in an interactive dashboard using Plotly.
It demonstrates the end-to-end data science workflow: data collection → data cleaning → data analysis → visualization.
🚀 Project Workflow
1️⃣ Data Collection
Stock Price Data
Collected using the yfinance library.
Tesla stock data (TSLA)
GameStop stock data (GME)
Revenue Data
Scraped using requests and BeautifulSoup from the assignment-provided HTML page.
Tesla Quarterly Revenue table
GameStop Quarterly Revenue table
2️⃣ Data Cleaning
Removed unwanted characters ($, ,, -) from revenue values.
Converted revenue values into numeric type.
Removed missing/empty rows.
Standardized column names (Date, Revenue).
Restricted revenue data to up to April 2021, as per assignment requirements.
3️⃣ Data Analysis
Explored Tesla and GameStop stock data with Pandas.
Checked quarterly revenue trends.
Ensured both stock and revenue datasets aligned in terms of time period.
4️⃣ Visualization (Dashboard)
Created interactive dashboards using Plotly with two subplots:
Row 1 → Historical Stock Closing Price (line plot)
Row 2 → Historical Revenue (line plot)
Two dashboards were built:
📈 Tesla Stock Price vs Revenue
📉 GameStop Stock Price vs Revenue
🛠️ Technologies Used
Python
Pandas (data manipulation)
yFinance (stock price data)
BeautifulSoup (bs4) + Requests (web scraping)
Plotly (dashboard visualization)
📷 Sample Output
Tesla Dashboard:
GameStop Dashboard:
📌 Key Learnings
Collecting financial data using APIs (yfinance).
Web scraping financial tables with BeautifulSoup.
Cleaning and preprocessing financial data.
Building interactive dashboards with Plotly.
Linking multiple data sources into one analysis pipeline.
✅ This project gives a clear picture of how stock price trends relate to company revenue, and serves as a practical example of data collection, cleaning, and visualization in real-world data science.
