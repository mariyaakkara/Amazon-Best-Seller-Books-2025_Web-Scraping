# Amazon-Best-Seller-Books-2025_Web-Scraping
This project features a complete data pipeline that scrapes real-time book data from Amazon, India’s bestsellers page. It handles data extraction, cleaning (automated currency formatting), and provides visual insights into pricing trends and reader ratings using Python's data science ecosystem.

🚀 Key Features
Web Scraping: Utilizes BeautifulSoup to extract book titles, authors, prices, and star ratings from dynamic HTML containers. 
Data Cleaning: A custom clean_price function that automatically strips currency symbols (₹) and commas to convert raw strings into usable numerical data.
Insights & Visualization: * Identifies the Top 10 Most Expensive Bestsellers through automated sorting. 
Generates high-quality visualizations using Seaborn and Matplotlib to display pricing distributions.
Exportable Data: Automatically saves all scraped findings into a structured Amazon_best_seller_books_2025.csv file for further analysis.

🛠️ Tech Stack
Language: Python
Libraries: Requests (HTTP calls), BeautifulSoup (Scraping), Pandas (Data Analysis), Seaborn & Matplotlib (Visualization)
