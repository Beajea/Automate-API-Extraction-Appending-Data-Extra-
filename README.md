# Automate-API-Extraction-Appending-Data-Extra-
Overview:
This repository contains a Python script for automated cryptocurrency data extraction using the CoinMarketCap API. The script fetches the latest cryptocurrency listings, appends the data to a Pandas DataFrame, and provides visualizations of cryptocurrency trends over time.

Key Features:
API Integration: Utilizes the CoinMarketCap API for real-time cryptocurrency data retrieval.
Data Processing: Pandas is employed to manipulate and normalize the obtained JSON data into a structured DataFrame.
Visualization: The project includes visualizations using Seaborn and Matplotlib to illustrate cryptocurrency price trends.
Prerequisites:
Python 3.x
Pandas, Requests, Seaborn, and Matplotlib libraries
How to Use:
Clone the repository to your local machine.
Install the required dependencies using pip install -r requirements.txt.
Run the script crypto_data_extraction.py to fetch and analyze cryptocurrency data.
Explore the generated visualizations in Jupyter Notebook or other compatible environments.
Notes:
The script runs at regular intervals, appending data to the existing CSV file (API.csv).
Adjust the time interval in the loop for your specific needs.

