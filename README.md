# Web Scraping: Key Events of the 20th Century
# This is a task for CF PM Data Visualization course

This project demonstrates basic web scraping using Python. The goal is to extract and save the content of the Wikipedia page on Key Events of the 20th Century for further analysis or reference.

Files
Task_1.4.ipynb
Uses Selenium and webdriver_manager to automate browser control.

Attempts to scrape the content of the Wikipedia page.

Also uses BeautifulSoup, though it redundantly includes Selenium for a static page.

Saves the scraped content to a file named Key_events_20th_century.

Task_1.4_updated.ipynb
Optimized and simplified version of the original.

Removed Selenium: since the target page is static (no JavaScript rendering needed), using requests + BeautifulSoup is more efficient.

Extracts only the main article content by targeting the <div class="mw-parser-output"> container.

Cleans and organizes text from <p>, <li>, <h2>, and <h3> tags.

Saves the final result to Key_events_20th_century.txt.