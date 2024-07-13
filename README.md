## Web Scraping and Data Analysis of President Trump's False Statements

## Introduction
In this project, we scrape data from an interactive feature on The New York Times website that lists false statements made by President Trump. We parse the HTML content using BeautifulSoup to extract relevant information such as the date of the statement, the false statement itself, an explanation of the falsehood, and a URL to the source debunking the claim. The extracted data is then structured into a pandas DataFrame for further analysis.

## Technologies Used
Python

requests library

BeautifulSoup library

pandas library

## Project Details
The project involves:

Fetching HTML content from a specific URL using the requests library.

Parsing the HTML content with BeautifulSoup to locate and extract relevant data.

Cleaning and structuring the extracted data into a pandas DataFrame.

Saving the DataFrame to a CSV file for future analysis or reporting.

## Files Included
webScraping.ipynb: Jupyter Notebook containing the Python code for scraping and analyzing the data.

trump_lies.csv: CSV file containing the cleaned and structured data extracted from the website.

## Setup Instructions
Install the required libraries: pip install requests beautifulsoup4 pandas

Open webScraping.ipynb in Jupyter Notebook or any compatible environment.

Run the notebook to execute the scraping and analysis scripts.

## Usage
Execute the cells in webScraping.ipynb to perform web scraping and generate the trump_lies.csv file.

Use the CSV file for further analysis, reporting, or visualization of the data.
