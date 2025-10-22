# 📚 Simple Study Scraper 🚀

A basic Python web scraper designed to extract the title and main paragraph content from a webpage. Perfect for quickly saving study materials or articles for offline reading!

## 📜 #Description

This project is a straightforward Python script that demonstrates the fundamentals of web scraping. It uses the `requests` library to fetch the HTML content of a webpage and `BeautifulSoup` (from `bs4`) to parse that content. The script specifically looks for the main title of the page (usually within an `<h1>` tag) and all paragraph text (within `<p>` tags), cleaning and saving them to a local `.txt` file.

It's an ideal tool for students, learners, or anyone who wants to quickly archive text-based content from the web without ads or navigation elements.

## ✨ #Features

* **Extracts Page Title:** Finds the main `<h1>` tag.
* **Grabs All Paragraphs:** Pulls text from all `<p>` tags.
* **Saves to File:** Saves the extracted content into a clean `.txt` file.
* **Browser Spoofing:** Uses a `User-Agent` header to mimic a browser.
* **Error Handling:** Includes basic `try...except` block.

## 🛠️ #How-to-Use

### 1. Prerequisites

* [Python 3.x](https://www.python.org/) 🐍
* The `requests` library
* The `beautifulsoup4` library

### 2. Installation

1.  **Clone the repository (or just save the script):**

    ```bash
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    cd your-repo-name
    ```

2.  **Install the required libraries:**

    ```bash
    pip install requests beautifulsoup4
    ```

### 3. Running the Script 🏃‍♀️

1.  Open the `scrape_study_content.py` file in your editor.

2.  Change the `url` variable to the webpage you want to scrape:

    ```python
    # --- Example: Try it with a webpage ---
    url = '[https://www.example.com](https://www.example.com)' # 👈 CHANGE THIS URL
    output_file = 'study_content.txt'
    ```

3.  Run the script from your terminal:

    ```bash
    python scrape_study_content.py
    ```

4.  Look for a new file named `study_content.txt` in the same directory. It will contain the scraped title and content! 📄

## ⚠️ #Disclaimer

This script is for educational purposes only. Please be responsible and respectful when scraping.

* ✅ **Always** check a website's `robots.txt` file first.
* ❌ **Never** scrape websites that explicitly forbid it.
* ❌ **Do not** overload a website with too many rapid reques
