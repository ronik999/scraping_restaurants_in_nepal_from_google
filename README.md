# Restaurant data scraping

Restaurants in Nepal is scraped which is provided by google using Selenium web automation. The data are then stored in csv file named as scraping.csv for storing all restaurants information and review.csv for restaurants review posted by the users in google.com
___
# Execution
1. Install all the required dependencies from requiremen.txt
2. Update the path of chrome driver on scrape.py and input the path where chromedriver is installed

        browser = webdriver.Chrome(executable_path='chromedriverpath',options=option)
3. Run __init__.py in terminal:

        python __init__.py
__



