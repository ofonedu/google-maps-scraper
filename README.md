# Google Maps Scraper

This python project is a scraper that fetches information about places (e.g., restaurants, doctors,lawyers etc.) from Google Maps. 
It uses the Google Places API to collect data like name, address, website, phone number, reviews, images, and more.
I implemented pagination logic to allow for maximum availale places allowed by google. 

## Features

- Fetches places based on location and keyword search.
- Retrieves detailed place information, including:
  - Name
  - Address
  - Website
  - Phone number
  - Reviews (filtered for ratings 4.5 and above)
  - Review Author and Pofile photo
  - Photos of business (image URLs)
- Saves the fetched data in JSON format.
- Supports pagination for large sets of results.

## Installation

### 1. Clone the repository

git clone https://github.com/your-username/google-maps-scraper.git
cd google-maps-scraper

### Create a python virtual environment and activate

python -m env /path to your project folder/

### Install required dependencies
pip install -r requirements.txt

### Goto google cloud console, create a new project, enable places API. Copy API credentials and replace in the project accordingly.

### Set seach parameters
location = "37.7749,-122.4194"  # San Francisco coordinates<br>
radius = 5000  # 5km radius<br>
keyword = "restaurant"<br>

run your code.





