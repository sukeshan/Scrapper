# Naukri Job Scraper 🔍

A simple Python web scraper that extracts job details from [Naukri.com](https://www.naukri.com) using Selenium and BeautifulSoup, then stores the data in MongoDB. 🚀

## Features ✨

- **Scrapes job listings:** Navigates through pages and extracts detailed job information.
- **Data extraction:** Retrieves job title, role, industry, department, description, skills, experience, posting date, employment type, education, company, and more.
- **Database storage:** Saves the extracted data into a MongoDB collection.
- **Headless operation:** Runs Chrome in headless mode for seamless scraping.

## Prerequisites ✅

- **Python 3.x**
- **Google Chrome** & [ChromeDriver](https://sites.google.com/chromium.org/driver/)
- Python packages:
  - [Selenium](https://selenium-python.readthedocs.io/)
  - [BeautifulSoup4](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
  - [pymongo](https://pymongo.readthedocs.io/)

## Installation 🔧

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd Scrapper/
   ```
   
2. **Install Dependencies:**
  ```bash
  pip install selenium beautifulsoup4 pymongo
  ```

3. **Download ChromeDriver:**

Ensure you download the version that matches your Chrome browser.


## Configuration ⚙️

MongoDB Connection:

Update the MongoDB connection string in the script if necessary:  
```bash
  client = MongoClient("mongodb://user_data_base")
```

## Usage 🚀

Run the scraper with:
```bash
python Naukri Scrapper.py
```
The script will:

- Navigate through job listing pages on Naukri.com.
- Extract detailed job information for each new listing.
- Insert the job data into your specified MongoDB collection.

