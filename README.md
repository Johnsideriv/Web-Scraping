# Web-Scraping
Web Scraping with Selenium:
from selenium import webdriver

# Set up the browser
driver = webdriver.Chrome()

# Navigate to a website
driver.get("https://example.com")

# Perform actions (click, input, etc.)
element = driver.find_element_by_id("example")
element.click()

# Extract data
data = driver.find_element_by_css_selector(".data").text

# Close the browser
driver.quit()
