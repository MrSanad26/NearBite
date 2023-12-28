# NearBite
This repository contains code for exploring and cleaning a dataset of restaurants and cafes in Saudi Arabia. The dataset was collected from Google Maps and includes information about ( 5000 rows ) such as the name, type, location, and working hours of each establishment.


- pandas
- numpy
- seaborn
- matplotlib

- You can install these libraries using pip:

- pip install pandas numpy seaborn matplotlib


## Data

- The dataset is divided into several CSV files, each containing information for a particular region of Saudi Arabia. The files are:

- Riyadh2.csv
- Al-Madina.csv
- Makkah_Jeddah_Taif.csv
- dammam_khobar_dhahran.csv
- Jeddah.csv
- Makkah_Jeddah_Taif.csv

# The columns of the dataset are:

- name: The name of the restaurant or establishment, as listed on Google Maps.
- type: The general category or type of the restaurant or establishment.
- phone: The phone number of the restaurant or establishment.
- full_address: The full address of the restaurant or establishment.
- street: The street address of the restaurant or establishment.
- city: The city or locality in which the restaurant or establishment is located.
- latitude: The latitude coordinate of the restaurant or establishment.
- longitude: The longitude coordinate of the restaurant or establishment.
- rating: The overall rating of the restaurant or establishment on Google Maps, out of 5.
- working_hours: The hours of operation, as a dictionary with keys for each day and operation hours as values.
- business_status: The current operational status of the restaurant or establishment on Google Maps.
- logo: A URL to the restaurant or establishment's logo on Google Maps.
- verified: A boolean indicating if the restaurant or establishment is verified by Google.
- location_link: A URL to the Google Maps page for the restaurant or establishment.


## Exploratory Data Analysis

- The code in this repository includes exploratory data analysis (EDA) of the dataset. The EDA includes:

- Merging all dataframes into one
- Removing unnecessary columns
- Cleaning missing data
- Mapping city and establishment types to standardized names
- Converting English day names in working_hours column to Arabic
- Creating a new feature, total_reviews, based on the reviews_per_score column

Please note that the total_reviews feature is not present in the original dataset, and was created as part of the EDA.

## Saudi Arabia Restaurant and Cafe Dataset Telegram Chatbot

This repository contains code for a Telegram chatbot that allows users to search for restaurants and cafes in Saudi Arabia. The chatbot is built using the python-telegram-bot library and uses the dataset in this repository to retrieve information on establishments.


https://github.com/MrSanad26/NearBite/assets/98082864/c7ceaf93-b616-4302-8605-da5eba29695b

