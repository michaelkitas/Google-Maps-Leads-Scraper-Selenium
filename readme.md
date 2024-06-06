# Google Maps Scraper

This Python application utilizes Selenium WebDriver to scrape data from Google Maps based on a specific search keyword. The data includes titles, links, websites, ratings, reviews, and phone numbers of the listed entities.

## Proxies Recommendation

By the way, using good quality proxies is crucial for scraping. I recommend using NodeMaven. Use `Michael` at checkout to get +2GB of free traffic when purchasing any package (except trials) - [https://go.nodemaven.com/scrape](https://go.nodemaven.com/scrape)

## Features

- Anonymize proxy usage to prevent blocking.
- Automated browser navigation and data scraping from Google Maps.
- Extraction of detailed information including business title, website, contact information, ratings, and reviews.
- Automated scrolling to load all search results.
- Data saved in an easy-to-read JSON format.

## Prerequisites

Before running this project, ensure you have the following installed:
- Python (3.6 or higher recommended)
- pip (usually comes with Python)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/michaelkitas/Google-Maps-Leads-Scraper-Selenium
   ```
2. Navigate to the project directory:
   ```bash
   cd google-maps-scraper-python
   ```
3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

To run the script, simply execute the following command in your terminal:

```bash
python scraper.py
```

Before running the script, you may want to set the search keyword and proxy settings in the script file:

```python
keyword = "your_search_keyword"
proxy = "http://username:password@proxy-host:proxy-port"
```

## Output

After running the script, the scraped data will be saved in a file named `results.json` in the root directory of the project. This file will contain an array of objects, each representing a business or entity found in the Google Maps search results.

## Configuration

You can modify the script to search for different keywords or to change the behavior of the scraping process. Configuration can be done directly in the script:

- Change the `keyword` variable to your desired search term.
- Modify the `proxy` variable to use different proxy settings.
- Adjust the scrolling behavior, timeout settings, and other parameters as needed.

## Disclaimer

This script is for educational purposes only. Scraping data from websites may be against their terms of service. Use this script responsibly and ethically, and ensure you are compliant with Google Maps' terms of service and any relevant laws or regulations.

## Contributing

Contributions to the project are welcome! Please feel free to fork the repository, make changes, and submit pull requests.
