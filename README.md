# GITHUB Topic Page along with their top 20 Repositories links Webscraping
- We are going to Scrape https://github.com/topics
- We will get a list of Topics, e.g Topic Title, Topic URL, Topic Description
- From each topic we will get top 20 repositories.
- From each topic we will grab the Username, Repository name, Repository URL and Stars.
- For each Topic we will create a CSV file and for top 20 repositories in each topic we wil create Data Folder and save .CSV files in it.

## TOOLS WE ARE USING FOR THIS PROJECT
- Python
- Requests
- BeautifulSoup
- Pandas

## HOW TO IMPLEMENT THAT TOOLS
- Use requests to download the target Page.
- Use BS4 to parse and extract information.
- Convert to a Pandas Dataframe.
