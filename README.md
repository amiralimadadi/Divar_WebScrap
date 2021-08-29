# Divar_WebScrap

In this project, I try to scrap data from [Tehran Divar](https://divar.ir/s/tehran) website with python programming language. 
This website is mainly designed for selling second hand stuffs, however after a while, there are some other services available in the website like housing.
I focused on the [Tehran Divar](https://divar.ir/s/tehran), which is dedicated for *Tehran city*. I scrap housing advertisings in *Tehran city*.

## Prerequisites
I use some famous python libraries like *requests*, *BeautifulSoup*, *pandas* and *numpy*. In order to do some specific activies, some other libraries seem to be necessary:
1.   selenium (for scrolling down the main page)
2.   unidecode and arabic_reshaper (for working with *Farsi characters*)
3.   progressbar (for shwoing the progress of link scraping)

**Tip** The instructio of *!pip install ...* is written in the notebook to ensure that all libraries are installed in the destination machine.

[ChromeDriver](https://chromedriver.chromium.org/) is also needed to open and scroll the web page. You need to download the suitable version based on your Operating System. ChromeDriver is an open source tool for automated testing of webapps. It provides capabilities for navigating to web pages, user input, JavaScript execution, and more. ChromeDriver is a standalone server that implements the W3C WebDriver standard.

## Files
1.   **Scrap.ipynb**: Contains the entire python code of project.
2.   **AdsUrl.txt**: Filled during running program, contains the url of housing advertisements.
3.   **Data.csv**: It is the dataset of housing in Tehran and is the final output of this project.
4.   **Chromedriver.exe**: It is used to open and scroll down the main web page.
