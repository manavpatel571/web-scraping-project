# **Yahoo Finance Mutual Funds Scraper**

**Description**

This Python script scrapes data on mutual funds from Yahoo Finance and saves it in a CSV file. The script uses the BeautifulSoup library to parse the HTML of the mutual funds page and extract the relevant data, which is then cleaned and organized into a pandas DataFrame.

**Dependencies**

To run this code, you will need:

- Python 3.x
- BeautifulSoup 4
- pandas
- requests

**Setup**

To use this script, simply download or clone the repository, navigate to the project directory, and run the following command:

python main.py

The script will scrape data on mutual funds from Yahoo Finance and save it in a file called mutual\_funds.csv.

**Data Sources**

The data in this project is scraped from Yahoo Finance ([https://ca.finance.yahoo.com/mutualfunds/](https://ca.finance.yahoo.com/mutualfunds/)). Please note that the terms of use for Yahoo Finance data prohibit commercial use and redistribution, so this code is intended for personal or educational use only.

**Data Processing**

The script extracts the following data for each mutual fund:

- Fund name
- Symbol
- Price
- Change
- Percent change
- Net assets
- YTD return

The data is then cleaned and organized into a pandas DataFrame, with column names matching the original data source.

**Outputs**

The output of this script is a CSV file called mutual\_funds.csv, which contains the scraped data in a tabular format. You can open this file in a spreadsheet program like Microsoft Excel or Google Sheets to view and analyze the data.

**Data Visualization:**

The script provides two examples of data visualization using the matplotlib library:

• A bar chart of the top 10 mutual fund companies by intraday price

• A scatter plot showing the relationship between the 200 day average and intraday price

**Summary Statistics:**

The script provides an example of summary statistics using the pandas library:

• A table of summary statistics for the data, including count, mean, standard deviation, minimum, maximum, and quartiles for numeric column

**Future Work**

Here are some ideas for future improvements or extensions to this code:

- Add support for scraping data on additional financial instruments, such as stocks or bonds
- Implement a scheduling or automation feature to scrape data at regular intervals
- Add functionality to visualize the scraped data using a library like matplotlib or seaborn
- To modify the code for data visualization, you can refer to the matplotlib documentation and examples, and customize the charts to suit your needs.

**Contact Information**

If you have any questions or feedback about this code, please feel free to contact the author at manavpatel5571@gmail.com.