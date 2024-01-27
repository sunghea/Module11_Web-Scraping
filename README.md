**# Module11_Web-Scraping repository shares files that have completed Part1 and Part2**

**Part 1: Mars News Scraping**
1.1 Automated Browsing and HTML Extraction
Utilized Splinter for automated browsing and Beautiful Soup for HTML extraction.
The code for this process is available in the file part_1_mars_news.ipynb.
1.2 Title and Preview Text Extraction
Successfully scraped and extracted titles and preview text from Mars news articles.
All extracted information is stored in a Python data structure—a list of dictionaries.
The output is saved as news_data.json.

**Part 2: Mars Weather Data Analysis**
2.1 HTML Table Extraction
Extracted Mars weather data into a Pandas DataFrame.
Either Pandas or Splinter and Beautiful Soup were used for data scraping.
Ensured correct headings and data types for all columns.
2.2 Data Analysis
General Questions:
Answered the following questions:
How many months exist on Mars?
How many Martian days' worth of data are there?
Detailed Data Analysis and Visualization:
Conducted a comprehensive analysis and created visualizations to answer the following questions:
Which month, on average, has the lowest and highest temperature?
Which month, on average, has the lowest and highest atmospheric pressure?
Estimated the number of terrestrial days in a Martian year with a visual representation within 25% accuracy.
2.3 Data Export
Exported the final DataFrame into a CSV file named mar_weather_data.csv.

**Files Uploaded:**
news_data.json: Contains scraped Mars news titles and preview text.
mar_weather_data.csv: CSV file with Mars weather data.
part_1_mars_news.ipynb: Jupyter notebook with code for Part 1.
part_2_mars_weather.ipynb: Jupyter notebook with code for Part 2.
