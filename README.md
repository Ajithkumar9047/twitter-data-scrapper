# Twitter Data Scraper

## Introduction

This Python application allows you to scrape Twitter data based on hashtags and date range. It is built using the following technologies:

- [Streamlit](https://www.streamlit.io/): A Python library for creating web apps for data science and machine learning.
- [Pandas](https://pandas.pydata.org/): A data manipulation and analysis library for Python.
- [Snscrape](https://github.com/JustAnotherArchivist/snscrape): A Python library for scraping social media content.

## Features

- Search for tweets by specifying a hashtag, date range, and data limit.
- View scraped tweets in a user-friendly table format.
- Download scraped data as a CSV file.
- Upload scraped data to MongoDB.
- Responsive and interactive user interface.

## Prerequisites

Before you begin, make sure you have the following installed:

- Python 3.x
- Streamlit
- Pandas
- Snscrape
- Pyrebase (Firebase)

## Getting Started

1. Clone this repository to your local machine:
   git clone https://github.com/yourusername/twitter-data-scraper.git
   cd twitter-data-scraper
   
2.Install the required Python libraries:

  pip install -r requirements.txt
  
3.Run the application:

streamlit run app.py
Open a web browser and go to http://localhost:8501 to use the application.

##Usage
Choose "Home" from the navigation menu to start scraping Twitter data.
Enter a hashtag, data limit, start date, and end date, then click "Search."
View the scraped tweets and download them as a CSV file.
Optionally, upload the scraped data to MongoDB.

##About Us
In this application, we use the snscrape module to scrape Twitter data.
The front end of the application is built using Streamlit.
The scraped data can be stored in MongoDB in the form of a dictionary.

##Version Information
Streamlit: 1.13.0
PyMongo: 4.2.0
Pandas: 1.5.0
Snscrape: 0.4.3.20220106

##License
This project is licensed under the MIT License. See the LICENSE file for details.
Replace `https://github.com/yourusername/twitter-data-scraper.git` with the actual URL 
