# TECHIN 510 - Lab 5 - Seattle Events App

https://techin510-ychen349-lab5.azurewebsites.net

# Seattle Events Interactive Data Visualization App

## Overview
This project provides an interactive platform for exploring and visualizing data pertaining to events in Seattle. Utilizing a custom dataset generated from web scraping, the application offers insights into categories, locations, dates, and weather conditions of events, enabling effective filtering and analysis of Seattle's event landscape.

## Project Structure
- `scraper.py`: A script that scrapes event and weather data from the Visit Seattle website and weather APIs, storing the data in a PostgreSQL database hosted on Azure.
- `app.py`: A Streamlit application for data visualization that allows users to interact with the dataset through various charts and filters.
- `db.py`: Contains utility functions for database connectivity.
- `data/`: A directory to store JSON files with scraped links and event data.

## Setup and Installation
Ensure Python 3.8+ is installed. Set up the environment, create a virtual environment, and install dependencies using the following commands:

```sh
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
pip install -r requirements.txt
