## PageObject pattern template
Python + Unittest + Selenium WebDriver + Chromedriver

###### Setup for Windows:

1. [download](https://www.python.org/ftp/python/3.6.4/python-3.6.4-amd64-webinstall.exe) & install python 3 if python is not in sys varaibles - [add it the same way as chromedriver](https://developers.thomsonreuters.com/sites/default/files/How%20To%20Add%20ChromeDriver%20To%20System%20Variables_0.pdf)
2. [download pip](https://bootstrap.pypa.io/get-pip.py)
3. python get-pip.py
4. pip install selenium
5. [download chromedriver](https://chromedriver.storage.googleapis.com/2.35/chromedriver_win32.zip)
6. [add chromedrive into syspath](https://developers.thomsonreuters.com/sites/default/files/How%20To%20Add%20ChromeDriver%20To%20System%20Variables_0.pdf) and copy the same path into ..unittests\base\config.py
7. open terminal as admin
```
python
from selenium import webdriver
webdriver.Chrome(r"path to chromedriver").get('https://google.com')
```