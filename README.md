<img src="/Images/MIT-Mars-Plan-01.jpg" width="500">

# Module 12 Challenge Submission - Web Scraping Challenge

#### This repository contains the code and resources for the Web Scraping Challenge, developed as part of Module 12 of the University of Western Australia's Data Analysis Bootcamp. In this project, we have utilized web scraping techniques to collect data related to Mars from different sources. The collected data has been analyzed using various Python libraries such as Beautiful Soup, Pandas, and Matplotlib.

## Table of Contents
- [Getting Started](#getting-started)
- [Project Deliverables](#project-deliverables)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [References](#references)

## Getting Started

These instructions will help you set up the project on your local machine for development and testing purposes.

### Prerequisites

Ensure you have Python 3.8+ installed on your system. You can check your Python version by running:

```python --version```

You will also need the following libraries:

- Pandas
- beautifulsoup4==4.10.0
- bs4==0.0.1
- pymongo==3.12.0
- selenium==3.141.0
- splinter==1.1.0
- webdriver-manager==3.5.0
- matplotlib==3.4.3
- pandas==1.3.3
- seaborn==0.11.2


## Project Deliverables

This project has two deliverables:

>`Deliverable 1`: **Scrape Titles and Preview Text from Mars News**

In this deliverable, we have scraped the titles and preview text from Mars news articles by following these steps:

Used automated browsing to visit the Mars NASA news site and inspect the page to identify which elements to scrape.

Created a Beautiful Soup object and used it to extract text elements from the website.

Extracted the titles and preview text of the news articles that we scraped and stored the scraping results in Python data structures.

Stored all the dictionaries in a Python list.

Printed the list in our notebook.

Optionally, stored the scraped data in a file or database (to ease sharing the data with others). To do so, we exported the scraped data to a JSON file or a MongoDB database.

>`Deliverable 2:` **Scrape and Analyze Mars Weather Data**

In this deliverable, we have scraped and analyzed Mars weather data by following these steps:

Used automated browsing to visit the Mars Temperature Data Site and inspected the page to identify which elements to scrape.

Created a Beautiful Soup object and used it to scrape the data in the HTML table.

Assembled the scraped data into a Pandas DataFrame.

Examined the data types that were currently associated with each column. If necessary, we cast (or converted) the data to the appropriate datetime, int, or float data types.

<img src="/Images/Titles & Previews.jpg" width="800">

Analyzed the dataset by using Pandas functions to answer the following questions:

- How many months exist on Mars?
- How many Martian (and not Earth) days worth of data exist in the scraped dataset?
- What are the coldest and the warmest months on Mars (at the location of Curiosity)?
- Which months have the lowest and the highest atmospheric pressure on Mars?
- About how many terrestrial (Earth) days exist in a Martian year?
- Exported the DataFrame to a CSV file.

<img src="/Images/avg_temp_mars.png" width="500">


<img src="/Images/avg_pa_mars.png" width="500">


<img src="/Images/daily_temp_mars.png" width="800">

## Conclusion

This project has provided us with an opportunity to apply web scraping techniques to collect and analyze data related to Mars. The project has helped us to develop our core skills of data collection, storage, analysis, and visualization. Through this project, we have gained a better understanding of the potential applications of web scraping in real-world scenarios.

## Project Structure

```
Images
   |-- Titles & Previews.jpg
   |-- avg_pa_mars.png
   |-- avg_temp_mars.png
   |-- daily_temp_mars.png
Notebooks
   |-- mars_data.csv
   |-- mars_news.json
   |-- part_1_mars_news.ipynb
   |-- part_2_mars_weather.ipynb
README.md
```
## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Acknowledgments
I would like to thank our bootcamp instructors for their guidance and support throughout this assignment.

## References
- Splinter: https://splinter.readthedocs.io/en/latest/
- BeautifulSoup: https://www.crummy.com/software/BeautifulSoup/bs4/doc/
- Selenium: https://www.selenium.dev/documentation/en/
- ChromeDriver: https://sites.google.com/a/chromium.org/chromedriver/
- webdriver_manager: https://github.com/gunthercox/webdriver_manager
- Pandas: https://pandas.pydata.org/docs/
- Matplotlib: https://matplotlib.org/stable/contents.html
- Seaborn: https://seaborn.pydata.org/tutorial.html
- University of Western Australia Data Analysis Bootcamp: https://bootcamp.ce.uwa.edu.au/data/






