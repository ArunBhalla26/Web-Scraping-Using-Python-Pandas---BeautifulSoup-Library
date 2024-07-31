# Amazon Product Scraper

This Python script scrapes product information from Amazon pages. It retrieves details such as product title, price, rating, number of reviews, etc. The data is then saved to a CSV file for further analysis.

## Features

- Extracts product titles, prices, ratings, number of reviews, and availability status , you can modify code to get other details as well.
- Handles different possible formats for product prices and ratings.
- Saves extracted data to a CSV file.

## Requirements

- Python 3.x
- `BeautifulSoup4`
- `requests`
- `pandas`
- `numpy`

I have used a Virtual environment for this project and added it to .gitignore .

You can install the required packages using :
pip install -r requirements.txt

## Example of Scraping Watches data :
- Step 1 : Setup every thing and run the file:
- ![2](https://github.com/user-attachments/assets/1c0bcf60-b858-47af-8f7e-045807109098)
- Step 2 : Copy link from amazon page and Past it in the terminal and hit Enter:
- ![4](https://github.com/user-attachments/assets/3b333d21-ea5f-4b1f-8be0-efa0d936e7ef)
- Step 3 : A CSV file is saved with the name amzon_data.csv that contains the data that we have scraped , It may takesome time if the amazon page contain huge information.
- ![5](https://github.com/user-attachments/assets/a94b424b-8018-4cb4-8f5c-7513fad2cdac)
- Step 4 : You can read the file in vs_code or in any csv reader
- ![6](https://github.com/user-attachments/assets/350ee355-2f4c-4120-8018-843517d32466)



