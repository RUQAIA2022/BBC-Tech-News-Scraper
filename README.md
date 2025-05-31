# BBC-Tech-News-Scraper

This Python project scrapes data from the BBC News Technology section using Selenium for browser automation.  
Its goal is to extract the first news article from the page, process its content, and save it in a structured format.


 What Does This Project Do?

- Automatically opens the BBC Tech News page.
- Bypasses the cookie consent popup (if present).
- Finds the first featured article on the page.
- Extracts the following data:
  -  Headline
  -  URL
  -  Summary
  - Current timestamp
- Saves the data in a file called `bbc_article.json`.


 Technologies & Tools Used:

 [Selenium](https://pypi.org/project/selenium/)  Web automation and interaction 
 [webdriver-manager](https://pypi.org/project/webdriver-manager/)  Automatically manages ChromeDriver 
 json ... Stores the extracted data in structured format 
 Python.. Main programming language  

