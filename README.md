# Mars Data Scraping

This project involves scraping data from two different websites related to Mars using Python libraries such as Splinter and BeautifulSoup. Below are the steps and code snippets for each part of the project.

## Scraping Mars News

### Step 1: Visit the Website
Using automated browsing, the code visits the Mars news site ([link](https://static.bc-edx.com/data/web/mars_news/index.html)).

### Step 2: Scrape the Website
Beautiful Soup is used to create an object to extract text elements from the website.

### Step 3: Store the Results
The titles and preview text of the news articles are extracted and stored in Python dictionaries. These dictionaries are then stored in a list.

## Scraping Mars Temperature Data

### Step 1: Visit the Website
Automated browsing is used to visit the Mars Temperature Data site ([link](https://static.bc-edx.com/data/web/mars_facts/temperature.html)).

### Step 2: Scrape the Table
Beautiful Soup is used to scrape the data in the HTML table. The data is then assembled into a Pandas DataFrame.

### Step 3: Store the Data
The scraped data is assembled into a Pandas DataFrame with columns corresponding to the table on the website.

## Data Analysis and Visualization

After scraping the data, some analysis and visualization are performed:

1. The number of months and Martian days' worth of data are calculated.
2. The average low temperature and atmospheric pressure by month are calculated and plotted.
3. The number of terrestrial (earth) days in a Martian year is estimated based on solar longitude data.
