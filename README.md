# LinkedIn Scraper

A Selenium based scraper that stores [LinkedIn](https://linkedin.com) profile data in a csv, and saves the profile to a pdf, and then follows the account.

## Usage

1. You must have python 3.6 installed.
```
git clone https://github.com/justinformentin/scrape-linkedin.git
cd ./scrape-linkedin
```
2. Install dependencies with 
```
pip install -r requirements.txt
```
3. Download the Google Chrome Driver [ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/)
```
mkdir chromedriver
```
5. Put the downloaded chromedriver.exe into the ./chromedriver folder you just created.
  a. A better idea would be to put chromedriver.exe in another folder that you can reference for multiple prjoects. All you have to do is      change the driver path on line 43.
```
python scrape.py
```
7. It will ask you for your linkedin email, password, then the job and location search parameters.
8. If you don't want to follow every profile, delete or comment out lines 101-107.
