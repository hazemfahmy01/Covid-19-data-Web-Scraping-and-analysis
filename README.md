# COVID-19 Data Scraping, Cleaning, and Analysis Project

This project aims to scrape, clean, and analyze data on COVID-19 from the Worldometer website. The data includes information on the number of confirmed cases, deaths, and recoveries of COVID-19 across different countries and regions.

## Website Scraping

The data was scraped from the [Worldometer website](https://www.worldometers.info/coronavirus/). We used Python and the Beautiful Soup library to scrape the data. We extracted the following data for each country:

- Country name
- Total cases
- New cases
- Total deaths
- New deaths
- Total recoveries
- Active cases
- Serious/critical cases
- Total cases/1M pop
- Deaths/1M pop
- Total tests
- Tests/1M pop

The scraped data was then formatted into DataFrame to keep appropriate Data from analysis, then saved in a CSV file for further analysis.

## Cleaning

Before analyzing the data, we needed to clean it by:

- Handling missing data
- Converting data types to their appropriate formats
- Dropping irrelevant columns

The cleaning process was carried out using Python and the pandas library.

## Analysis

After cleaning the data, we performed several analyses to gain insights into the dataset. The analyses included:

- Visualizing the distribution of COVID-19 cases across different countries and regions.
- Examining the relationship between the number of confirmed cases and the number of deaths.

The analyses were performed using Python and various data visualization libraries, including plotly and seaborn.

## Files

- `world_data_updated.csv`: This file contains the scraped and cleaned version of the COVID-19 data.
- `Covid_data_web_scraping_and_analysis.ipynb`: This Jupyter Notebook contains the Python code used for scraping, cleaning, and analyzing the data.

## Conclusion

The COVID-19 dataset provided valuable insights into the spread and impact of COVID-19 across different countries and regions. The scraping, cleaning, and analysis process helped us better understand the dataset and draw meaningful conclusions. We hope that this project can serve as a useful resource for anyone interested in exploring COVID-19 data

## Note:
The data in the saved file (.csv) and analysis is updated every time the script is run, as it scrapes and retrieves the latest real-time data from the Worldometer website.

## Google Colab Notebook Link :
https://colab.research.google.com/drive/1sXtpmFiVsRFESiuufeAENXYnvjUP_JnY?usp=sharing

You Can Run it! 
