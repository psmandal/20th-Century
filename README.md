# Web Scraping: Key Events of the 20th Century
# This is a task for CF PM Data Visualization course

This project demonstrates basic web scraping using Python. The goal is to extract and save the content of the Wikipedia page on Key Events of the 20th Century for further analysis or reference.

## Repository Contents

| File/Folder                         | Description |
|------------------------------------|-------------|
| `.gitignore`                       | Specifies files and folders to be excluded from version control. |
| `20th_century_scrape.ipynb`        | Web scraping notebook for collecting 20th-century text data. |
| `20th_century_text mining.ipynb`   | Core text mining and NLP notebook analyzing historical patterns. |
| `Key_events_20th_century/`         | Folder containing resources and results related to key historical events. |
| `Key_events_20th_century.txt`      | Raw text file listing major events from the 20th century. |
| `README.md`                        | You're reading it! |
| `Task_1.4.ipynb`                   | A specific subtask or milestone (e.g., sentiment or POS analysis). |
| `countries_list_20th_century.csv`  | List of country names used for text matching and analysis. |
| `country_list.ipynb`               | Notebook for analyzing and matching countries in text data. |
| `requirements.txt`                 | Standard package list to set up the Python environment. |
| `requirements_v2.txt`              | Extended or updated version of the requirements list. |
| `test.ipynb`                       | Scratchpad or testing notebook for quick code checks and trials. |


Task_1.4.ipynb
Uses Selenium and webdriver_manager to automate browser control.

Attempts to scrape the content of the Wikipedia page.

Also uses BeautifulSoup, though it redundantly includes Selenium for a static page.

Saves the scraped content to a file named Key_events_20th_century.

Task_1.4_updated.ipynb
Optimized and simplified version of the original.

Removed Selenium: since the target page is static (no JavaScript rendering needed), using requests + BeautifulSoup is more efficient.

Extracts only the main article content by targeting the <div class="mw-parser-output"> container.

Cleans and organizes text from to capture headings, paragraphs, and bullet points.

Saves the final result to Key_events_20th_century.txt.