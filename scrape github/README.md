# **GitHub Topic and Repository Scraper**

This project scrapes the GitHub website to retrieve information about topics and repositories based on the topic name.

**Installation**

1. Clone the repository to your local machine
2. Install the required libraries using the following command: pip install -r requirements.txt

**Usage**

1. Run the main.py file to scrape the GitHub website.
2. You will be prompted to enter the name of the topic you want to search for.
3. The program will then retrieve the top 30 repositories for that topic, along with the repository owner's username and the number of stars the repository has.
4. The output will be saved to a CSV file named repositories.csv.

**Libraries Used**

- pandas
- requests
- BeautifulSoup

**Future Work**

- Add functionality to retrieve more information about the repositories, such as the number of forks, the programming language used, etc.
- Improve the user interface by creating a web application.

**Contact Information**

If you have any questions or feedback about this code, please feel free to contact the author at manavpatel5571@gmail.com.