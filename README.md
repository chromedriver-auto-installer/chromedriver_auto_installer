# chromedriver_auto_installer

The project was created based on an abandoned project https://github.com/yeongbin-jo/python-chromedriver-autoinstaller.git

## Functionality
 - Automatically download chrome driver
 - Automatically install chrome driver

## Suport OS
 - Linux
 - MacOS
 - Windows

## Development and contributin rep
```
https://github.com/chromedriver-auto-installer/chromedriver_auto_installer_dev.git
```


## Installation (Temporarily unavailable)

```
pip install chromedriver_auto_installer
```
or
```
poetry add chromedriver_auto_installer
```

## Usage
```
import chromedriver_autoinstaller
chromedriver_auto_installer.install() 
```

## Example
```
from selenium import webdriver
import chromedriver_autoinstaller


chromedriver_autoinstaller.install()

driver = webdriver.Chrome()
driver.get("http://www.python.org")
```

