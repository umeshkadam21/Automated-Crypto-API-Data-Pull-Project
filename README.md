#  Automated Crypto API Data Pull

An automated cryptocurrency data pipeline built with **Python** that retrieves live market data from the CoinMarketCap API, processes it using **Pandas**, and generates insightful visualizations using **Seaborn** and **Matplotlib**.

This project enables automated daily crypto analytics for trend tracking and data-driven decision-making.



##  Project Overview

This project automates the process of:

* Pulling real-time cryptocurrency data from the CoinMarketCap API
* Cleaning and structuring JSON responses
* Transforming data into Pandas DataFrames
* Generating trend and performance visualizations
* Automating daily data retrieval for up-to-date analysis

The goal is to streamline crypto market analysis through automation and reproducible data workflows.



 ##  Tech Stack

* Python
* Pandas
* Seaborn
* Matplotlib
* Requests
* CoinMarketCap API



##  Project Structure

```
Automated-Crypto-API-Data-Pull/
│
├── crypto_data_pull.py        # Main automation script
├── data/                      # Stored raw & processed data
├── visualizations/            # Generated charts & graphs
├── requirements.txt           # Project dependencies
└── README.md                  # Project documentation
```


##  Features

###  Automated API Integration

* Connects securely to the CoinMarketCap API
* Fetches live cryptocurrency market data
* Supports customizable query parameters

###  Data Cleaning & Structuring

* Parses JSON responses
* Converts data into structured Pandas DataFrames
* Handles missing values and formatting

###  Data Visualization

* Trend analysis using Seaborn
* Performance comparisons using Matplotlib
* Market cap and price movement insights

###  Automation

* Designed for scheduled daily execution
* Enables continuous analytics updates
* Supports decision-making with fresh market data



##  Example Insights

* Top-performing cryptocurrencies by percentage gain
* Market capitalization comparisons
* 24-hour price movement trends
* Volume-based performance analysis



## Sample Visualization

The project generates visualizations such as:

* Price trend charts
* Market cap distribution graphs
* Performance comparison bar charts



##  Key Learnings

* Working with REST APIs
* JSON parsing and data structuring
* Data cleaning and transformation
* Building automated data pipelines
* Data visualization best practices



##  Future Improvements

* Add database storage (PostgreSQL / MongoDB)
* Build interactive dashboards (Plotly / Streamlit)
* Add historical trend analysis
* Deploy as a web application
