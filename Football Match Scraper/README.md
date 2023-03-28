# **Scrape data using Selenium**

**Overview**

This Python script uses the Selenium library to scrape data from a webpage and save it in a CSV file. The script opens a Firefox web browser, navigates to the target page, selects some options from a dropdown menu, clicks on a button, and extracts data from a table. The extracted data is then cleaned and organized into a pandas DataFrame, and saved to a CSV file.

**Dependencies**

To run this code, you will need:

- Python 3.x
- Selenium
- pandas

**Setup**

1. Clone the repository or download the files.
2. Install the required libraries by running the following command in your terminal or command prompt:

pip install selenium pandas

1. Download the Firefox web driver from the following link: [https://github.com/mozilla/geckodriver/releases](https://github.com/mozilla/geckodriver/releases)
2. Extract the geckodriver executable file and save it in a folder of your choice.
3. Modify the path variable in the script to match the path of the geckodriver executable on your system.
4. Run the script with the following command:

python scraper.py

1. The script will scrape data from the webpage and save it in a CSV file called data.csv in the same directory as the script.

**Webpage**

The data in this project is scraped from the following webpage: [https://www.adamchoi.co.uk/overs/detailed](https://www.adamchoi.co.uk/overs/detailed)

**Data Processing**

The script extracts the following data for each match:

- Date
- Home team
- Score
- Away team

The data is then cleaned and organized into a pandas DataFrame, with column names matching the original data source.

**Outputs**

The output of this script is a CSV file called data.csv, which contains the scraped data in a tabular format. You can open this file in a spreadsheet program like Microsoft Excel or Google Sheets to view and analyze the data.

**Future Work**

Here are some ideas for future improvements or extensions to this code:

- Add support for scraping data from additional webpages or tables.
- Implement error handling and logging to make the script more robust.
- Add functionality to visualize the scraped data using a library like matplotlib or seaborn.

**Contact Information**

If you have any questions or feedback about this code, please feel free to contact me on [manavpatel5571@gmail.com](mailto:manavpatel5571@gmail.com) .