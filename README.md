ETL Project: House Price Data Scraping and Loading to Snowflake

This project demonstrates a full ETL (Extract, Transform, Load) pipeline for scraping house price data from the web, processing and cleaning the data using Python, and loading the final dataset into a **Snowflake** data warehouse for analytics and reporting.

## 🚀 Project Overview

This project:
- **Extracts** housing data through web scraping
- **Transforms** the data using Python for cleaning and formatting
- **Loads** the final dataset into **Snowflake**

The goal is to automate the data ingestion process for property listings, making it readily available for analysis or integration into BI tools.



## 🔧 Technologies Used

* **Python** – Data extraction and transformation
* **BeautifulSoup** – Web scraping
* **Pandas** – Data cleaning and manipulation
* **Snowflake** – Cloud data warehouse (for the Load phase)
* **Jupyter Notebook** – Interactive development

## 📊 ETL Workflow

1. **Extract**

   * Scrape house price listings from a real estate website
   * Parse HTML using BeautifulSoup to extract relevant fields (e.g., address, price, bedrooms, etc.)

2. **Transform**

   * Clean missing values and standardize column formats
   * Convert currencies and normalize numerical data
   * Filter or sort properties as needed for business logic

3. **Load**

   * Establish a connection to Snowflake using `snowflake-connector-python`
   * Create and populate target tables in Snowflake
   * Commit the final dataset to a Snowflake schema for downstream analytics




