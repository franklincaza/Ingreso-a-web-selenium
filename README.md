# Ingreso-a-web-selenium

from selenium import webdriver
##from selenium.webdriver.common.keys import keys
from selenium.webdriver.common import keys


driver=webdriver.Chrome(executable_path=r"C:\Users\framirezh\OneDrive - Turia\Documents\Drivers\chromedriver.exe")

driver.get("https://www.google.com/")
print(driver.title)
