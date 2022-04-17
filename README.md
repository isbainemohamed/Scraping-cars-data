# Scraping-cars-data
In this project, we have manipulated some scraping technics while getting cars data using selenium. 

## Introduction:

**This Project has been done by : [LABRIJI SAAD](https://www.kaggle.com/saadlabriji) and [ISBAINE MOHAMED](https://www.kaggle.com/mohamedisbaine) and Supervised By: [Ikram EL ASRI](https://www.kaggle.com/ikramelasri)**

Pricing a car can usually be a difficult task
even for car enthusiasts and experts because 
cars have many features that affect prices 
more or less strongly, which could lead people 
without any knowledge in vehicles to be easily 
ripped off. To solve this kind of problem, we 
thought my teammate and I that we could use 
the modest knowledge we acquired in data 
science courses this year, to develop an 
machine learning model to price cars more 
accurately, or at least get an idea of the price 
range.

In this project we aim to scrape cars data from wandaloo

> Launched in May 2011 and published by the company INNOWEBB, wandaloo.com brings together all the information and help tools necessary to facilitate and carry out a transaction of sale or purchase of a new or used vehicle, a motorcycle, or an automotive accessory.

> wandaloo.com is also the leading comparison site and online car-motorcycle buying guide in Morocco. With its diversified offer, it very quickly became the essential automotive reference in the Kingdom, and this allows the connection between dealers and customers wishing to acquire a new car or motorcycle.

> wandaloo.com also offers auto-moto editorial content updated daily and covering all the news in Morocco and abroad. All the news, national and world premieres, events and fairs are present on wandaloo.com™ through reports, articles and essays. Everything is illustrated by the latest multimedia means.

> wandaloo.com™ offers a platform for publishing classified ads for used cars, used motorcycles and automotive accessories on the Internet. Thanks to its user-friendliness, its advanced functionalities, and its powerful and precise search engine, the sale and purchase of a used vehicle has never been so easy, intuitive and targeted.


## **Project Structure:**

**The project is divided into 3 major parts:**

> **1- Scrape cars data from the website**

> **2- Preprocess the data**

> **3- Build many Machine Learning models to predict cars prices**


**Web scraping** is the process of using bots to extract content and data from a website. Unlike screen scraping, which only copies pixels displayed onscreen, web scraping extracts underlying HTML code and, with it, data stored in a database. The scraper can then replicate entire website content elsewhere.

Data is an important asset in an organisation and web scraping allows efficient extraction of this asset from various web sources. Web scraping helps in converting unstructured data into a structured one which can be further used for extracting insights.

> **1| Beautiful Soup**

Beautiful Soup is a Python library for pulling data out of HTML and XML files. It is mainly designed for projects like screen-scraping. This library provides simple methods and Pythonic idioms for navigating, searching, and modifying a parse tree. This tool automatically converts incoming documents to Unicode and outgoing documents to UTF-8. 


> **2| LXML**

The lxml is a Python tool for C libraries libxml2 and libxslt. It is recognised as one of the feature-rich and easy-to-use libraries for processing XML and HTML in Python language. It is unique in the case that it combines the speed and XML feature of these libraries with the simplicity of a native Python API and is mostly compatible but superior to the well-known ElementTree_API. 

> **3| MechanicalSoup**

MechanicalSoup is a Python library for automating interaction with websites. This library automatically stores and sends cookies, follows redirects and can follow links and submit forms. MechanicalSoup provides a similar API, built on Python giants Requests (for HTTP sessions) and BeautifulSoup (for document navigation). However, this tool became unmaintained for several years as it didn’t support Python 3. 

> **4| Python Requests**

Python Requests is the only Non-GMO HTTP library for Python language. It allows the user to send HTTP/1.1 requests and there is no need to manually add query strings to your URLs, or to form-encode your POST data. There are a number of feature support such as browser-style SSL verification, automatic decompression, automatic content decoding, HTTP(S) proxy support and much more. Requests officially support Python 2.7 & 3.4–3.7 and runs on PyPy.

> **5| Scrapy**

Scrapy is an open-source and collaborative framework for extracting the data a user needs from websites. Written in Python language, Scrapy is a fast high-level web crawling & scraping framework for Python. It can be used for a wide range of purposes, from data mining to monitoring and automated testing. It is basically an application framework for writing web spiders that crawl web sites and extract data from them. Spiders are the classes that a user defines and Scrapy uses the Spiders to scrape information from a website (or a group of websites).

> **6| Selenium**

Selenium Python is an open-source web-based automation tool which provides a simple API to write functional or acceptance tests using Selenium WebDriver. Selenium is basically a set of different software tools each with a different approach to supporting test automation. The entire suite of tools results in a rich set of testing functions specifically geared to the needs of testing of web applications of all types. With the help of Selenium Python API, a user can access all functionalities of Selenium WebDriver in an intuitive way. The currently supported Python versions are 2.7, 3.5 and above. 

> **7| Urllib**

The urllib is a Python package which can be used for opening URLs. It collects several modules for working with URLs such as urllib.request for opening and reading URLs which are mostly HTTP, urllib.error module defines the exception classes for exceptions raised by urllib.request, urllib.parse module defines a standard interface to break Uniform Resource Locator (URL) strings up in components and urllib.robotparser provides a single class, RobotFileParser, which answers questions about whether or not a particular user agent can fetch a URL on the Web site that published the robots.txt file.

In our project we are going to use selenium.

WebDriver is an open source framework from the Selenium that can initiate a web browser, through the respective browser’s driver server, and control various aspects of the browser including, but not limited to text input and exploratory testing. Selenium Webdriver was the first testing framework that allowed for controlling the browser at the Operating System level.

![image.png](attachment:3c378387-71e7-466a-b832-b57a693fe5ad.png)
