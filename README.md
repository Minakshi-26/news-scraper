# News Scraper

A Python-based **News Scraper** that collects the latest headlines from multiple news websites, including **BBC News, Hindustan Times, and Times of India**.  
Headlines are saved in a timestamped `.txt` file and also printed in the console.

## Features
- Scrapes news headlines from **3 major sources**: BBC, Hindustan Times, Times of India  
- Removes duplicate headlines  
- Saves headlines in a **timestamped text file** for reference  
- Console output shows progress and number of headlines saved  

## Technologies Used
- Python 3.x
- `requests` for HTTP requests
- `BeautifulSoup` (bs4) for HTML parsing
- `datetime` for timestamping files

## Setup Instructions
1. Clone the repository:
git clone https://github.com/username/news_scraper.git

2. Navigate to the project folder:
cd news_scraper

3. (Optional) Create a virtual environment:
python -m venv venv
venv\Scripts\activate 

4. Install required libraries:
pip install requests beautifulsoup4

## Run Instructions
python news_scraper.py
* The script will fetch the latest headlines and save them to a file like:
  `headlines_2025-08-13_22-30.txt`
* The console also prints each headline with its source.

