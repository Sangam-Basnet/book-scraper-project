# Global Book Catalog Scraper 📚

This project is a Python-based web scraper designed to collect a comprehensive dataset from the public sandbox site 'books.toscrape.com'. The script automatically navigates through all 50 pages of the website's catalog to extract detailed information for all 1,000 books.

The result is a clean, structured, and ready-to-use CSV file, perfect for data analysis and machine learning tasks.

## Skills Demonstrated
- **Web Scraping:** Using `requests` to fetch web pages and `BeautifulSoup` to parse complex HTML.
- **Automation & Pagination:** The script intelligently finds and follows "next page" links to scrape an entire multi-page website.
- **Data Wrangling:** Collected data is cleaned, structured, and loaded into a pandas DataFrame.
- **Data Export:** The final dataset is saved as a clean `books_dataset.csv` file.
- **Version Control:** The project is managed and versioned using Git and hosted on GitHub.

## The Dataset (`books_dataset.csv`)
The dataset created by this scraper contains the following columns:

- `Title`: The title of the book.
- `Price`: The price in British Pounds (£).
- `Stock Availability`: The number of copies available.
- `Rating`: A numerical star rating from 1 to 5.
- `Category`: The genre or category of the book.
- `Description`: The full text of the book's synopsis.

## How to Run This Project
1.  Clone this repository to your local machine.
2.  Ensure you have the required Python libraries installed:
    ```bash
    pip install requests beautifulsoup4 pandas
    ```
3.  Open and run the `book_scraper.ipynb` notebook. The script will execute and generate the `books_dataset.csv` file in the same directory.
