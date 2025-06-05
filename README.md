# Amazon-Company-Stock-Value-and-Growth Study

📈 Amazon Stock Value & Growth Analysis

This project investigates the historical stock prices and revenue trends of Amazon (AMZN). Using Python, financial data is retrieved from Yahoo Finance and Macrotrends, cleaned, analyzed, and visualized to explore the company’s performance over the past year.

⸻

🧰 Tools and Libraries
	•	pandas
	•	numpy
	•	matplotlib
	•	plotly
	•	yfinance (or pandas_datareader, if using older Yahoo API)
	•	BeautifulSoup (for scraping Macrotrends revenue data)
	•	requests
	•	datetime

⸻

📁 Contents
	•	Data Retrieval:
	•	Amazon stock prices from Yahoo Finance
	•	Revenue data scraped from Macrotrends
	•	Data Cleaning:
	•	Removing symbols and formatting from revenue fields
	•	Converting dates and monetary values to appropriate types
	•	Visualization:
	•	Line plots of stock performance over time
	•	Combined revenue and stock price trends using Plotly

⸻

▶️ How to Run
	1.	Install dependencies (use virtual environment recommended):

pip install pandas matplotlib plotly yfinance beautifulsoup4 html5lib requests


	2.	(Optional): If using pandas_datareader, ensure you install:

pip install pandas_datareader
pip install setuptools  # For distutils on Python 3.12+


	3.	Run the notebook:
Open Amazon Company Stock Value and Growth Study - ISQ.ipynb in Jupyter or VSCode.

⸻

📊 Example Output
	•	Amazon stock trend over the last 12 months
	•	Quarterly revenue growth visualization
	•	Combined interactive Plotly graph with stock vs. revenue comparison

⸻

💡 Notes
	•	Macrotrends may block bots; make sure you set a valid User-Agent header in requests.
	•	Revenue data must be cleaned before converting to numeric type.
	•	For dynamic websites or blocked access, consider using Selenium.

⸻

📜 License

MIT License (or specify your own)

