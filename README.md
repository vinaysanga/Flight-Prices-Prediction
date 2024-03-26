# Flight prices prediction
This project presents a systematic approach to Exploratory Data Analysis (EDA) of flight data obtained from Online Travel Agent (OTA) websites such as Booking.com, Momondo, and Kayak. Web scraping techniques are employed to collect comprehensive flight information, including prices, airlines, departure times, arrival times, layover cities, layover times, aircraft types, and trip durations. The collected dataset is cleaned and preprocessed for data quality and consistency.

## 1. Introduction

Flight booking websites provide a convenient way for travelers to compare prices and book flights. The report addresses the challenge of sifting through overwhelming options by employing web scraping techniques to collect relevant flight data. The focus is on acquiring consistent and instant data from OTA websites for in-depth analysis.

## 2. Data Collection

### 2.1 Data Understanding

The report defines key data elements to be extracted, such as price, number of stops, airline, departure time, arriving time, and more. The data structure on OTA websites is analyzed to facilitate scraping.

### 2.2 Data Scraping

We collected the data from Momondo, Book- ing.com, and Kayak for the flights between Helsinki Vantaa (HEL) - Paris Charles de Gaulle (CDG) on 25th October. The tools available for scraping the data are BeautifulSoup and Se- lenium Web Driver. Since these are dynamic websites, we used the Selenium Web Driver to interact with them and collect the data. The dataset contains the following information:

- **Layover**: The layover in the journey
- **Stops**: Total number of stops
- **Duration**: The flight duration (including layover)
- **Departure**: The departure time from HEL
- **Arrival**: The arrival time at CDG
- **Carriers**: The airline names
- **Aircrafts**: The aircraft type (if available)
- **Price**: The cost of the ticket (in USD)
- **Site**: The flight aggregator where the data was taken from

**For the entire info, please check [MP1_Report](https://github.com/vinaysanga/EDISS-Data-Science/blob/master/Mini%20Project%201/MP1_Report.pdf)**