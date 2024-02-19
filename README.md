# T20-world-cup-cricket-data-analytics
## About

In this Project, I used cricket T20 world cup (2022) data to provide insights into the best 11-player lineup that could play for my team. I collected data from the espncricinfo website using Bright Data web scraping, transformed and cleaned the data in Pandas, and then created dashboards in Power BI.

## About dataset:

The Dataset is obtained from [T20 World cup](https://www.espncricinfo.com/records/tournament/team-match-results/icc-men-s-t20-world-cup-2022-23-14450). I used web scraping to gather data from the Bright Data website. I gathered four datasets from this website: batting summary, bowling summary, player information, and match results. The data I collected from Bright Data is in JSON (Java Script Object Notation) format.
here are the code that i used for webscrapping: [Web Scrapping code](web_scrapping_codes.zip)


## Data Transformation and cleaning:

The data obtained from bright data is in JSON (Java Script Object Notation) format.  json files more complex to parse and clean because the data has nested structures or irregular formatting.morever json needs more preprocessing for  because of their complex data structures.CSV (Comma-Separated Values)  store tabular data in a plain text format with rows and columns separated by commas. They are simple and easy to understand.Cleaning tasks such as removing duplicates, handling missing values, and converting data types are straightforward with CSV files which is comparitively hard in JSON files. so I want to transform my data from JSON format to CSV format with the help of Pandas in Python. 
Here is my code for my data preprocessing with the help of pandas: [t20 Data Processing](t20_data_preprocessing.ipynb)

## Data visualization:
Here is my power BI dashboard link: [t20 world cup  cricket dashboard](T20_world_cup Cricket Dashboard.pbix)





