# uwajimaya-scraper
A Japanese grocery store, located in the PNW, has a small, but informative directory of ethnic items and recipes

This project does require Selenium. If you haven't heard of Selenium, it is an automated way in accessing webpages. I prefer using Selenium over other web scraping methods because it lets you interact with the website more than BeautifulSoup or ElementTree would allow. 

Additionally, you need to add a webdriver. Either GeckoDriver (Firefox) or ChromeDriver (Chrome) would work. This allows Selenium to open your desired browser and interact with the web contents. The attached code does use ChromeDriver, so if you prefer GeckoDriver, you will need to change 'webdriver.Chrome()' to 'webdriver.Firefox() on lines 20 and 73.

I have attached the documents created from this script.

In further commits, I will look into separating out the ingredients and prepartions from the recipes with the possibility of linking items to these ingredients too.
