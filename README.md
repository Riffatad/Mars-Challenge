# Mars-Challenge
This project scrapes titles and preview text from Mars News articles using Python.The scraper accesses the Mars News website, extracts article titles and previews, and stores them in a list of dictionaries, providing a structured way to analyze Mars-related news.Optional: Data can be saved to a JSON file for easy sharing or analysis.
Prerequisites: Install the following Python packages:
splinter – for automated browser control
BeautifulSoup from bs4 – for HTML parsing
requests – for HTTP requests
json – for saving data as JSON (optional)
Installation command:
Open the Jupyter Notebook part_1_mars_news.ipynb.
Run each cell in order:
Splinter opens the Mars News website and BeautifulSoup parses the HTML.
Article titles and previews are extracted and stored in a dictionary format with keys title and preview.
Each dictionary is appended to a list.
Optional: Save data to mars_news.json by running the final cell for later access.
The data list is printed for quick review at the end of the notebook.
The notebook provides a flexible template for web scraping, allowing for adjustments to other sites by modifying the URL and parsing parameters.






