# AUTOMATION WITH PYTHON
# from selenium import webdriver
# from selenium.webdriver.common.by import By
# from selenium.webdriver.common.keys import Keys
# from chromedriver_py import binary_path



# driver = webdriver.Chrome(binary_path)

# driver.get('https://www.amazon.com/')

# searchbar = driver.find_element(By.ID, 'twotabsearchtextbox')
# searchbar.clear()
# searchbar.send_keys('Iphone 13')
# searchbar.send_keys(Keys.ENTER)


#YOUTUBE

# from selenium import webdriver
# from selenium.webdriver.common.by import By
# from selenium.webdriver.common.keys import Keys
# from chromedriver_py import binary_path
# from time import sleep



# driver = webdriver.Chrome(binary_path)

# driver.get('https://www.youtube.com/')
# driver.implicitly_wait(10)

# searchbar = driver.find_element(By.NAME, 'search_query')
# searchbar.clear()
# searchbar.send_keys('Covenant Christian Centre')
# sleep(5)
# searchbar.send_keys(Keys.ENTER)
# sleep(15)
# driver.close()


#BEST BUY

from selenium import webdriver
from selenium.webdriver.common.by import By
from selenium.webdriver.common.keys import Keys
from chromedriver_py import binary_path
from time import sleep



driver = webdriver.Chrome(binary_path)

driver.get('https://www.bestbuy.com/')
# driver.implicitly_wait(10)

searchbar = driver.find_element(By.ID, 'gh-search-input')
searchbar.clear()
searchbar.send_keys('Iphone 13')
sleep(5)
searchbar.send_keys(Keys.ENTER)
sleep(15)
driver.close()
