# AmazonApplePhoneWebScraping
Web scraping is the process of automating the extraction of data from websites. 

GOAL:

    Extracting information about Apple iphones sold on Amazon.
    Why Would You Want To Do This?
    - Price Tracking: Monitor price changes over time.
    - Product Comparison: Compare Apple phones across various sellers.
    - Review Analysis: Collect and analyze user reviews.
    

APPROACH FOR THE PROJECT:
  
    1. Sending Requests:
      - Used libraries like requests to send HTTP requests to Amazon pages.
      - Retrieved the HTML content of product pages.

    2. Parsing HTML:
      - Used tool BeautifulSoup to parse the HTML content.
      - Extracted specific data such as price, title, ratings, reviews using CSS selectors.

    3. Storing Data:
      - Saved the extracted data to a file (CSV).
   

TOOLS:

     Request, BeautifulSoup

PYTHON NOTEBOOK:

    https://github.com/pheonix2109/AmazonApplePhoneWebScraping/blob/main/Amazon_WebScrapping_Final.ipynb

OUTPUT CSV:

     https://github.com/pheonix2109/AmazonApplePhoneWebScraping/blob/main/Amazon_iphone16.csv
