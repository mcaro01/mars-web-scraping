# mars-web-scraping
Mars-Web-Scraping
Overview:

This new assignment consists of two technical products.  

Part 1: Scrape titles and preview text from Mars news articles.

Part 2: Scrape and analyze Mars weather data, which exists in a table.

Part 1: Scrape Titles and Preview Text from Mars News

Using Splinter, an automated browsing was used to visit the Mars news site. Then, extracted the HTML code with Beautiful Soup. After that, Inspected the page to 

identify which elements to scrape by using Chrome DevTools.

Extracted the titles and preview text of the news articles and stored them in a dictionary.

Used automated browsing to visit the Mars news site Links to an external site. 

Created a Beautiful Soup object and extracted text elements from the website.

Extracted the titles and preview text of the news articles scraped. Stored the scraping results in Python data structures as follows:

Stored each title-and-preview pair in a Python dictionary. Each dictionary has two keys: title and preview. 

{'title': "NASA's MAVEN Observes Martian Light Show Caused by Major Solar Storm", 
 'preview': "For the first time in its eight years orbiting Mars, NASA’s MAVEN mission witnessed two different types of ultraviolet aurorae simultaneously, the result of solar storms that began on Aug. 27."}

Stored all the dictionaries in a Python list.

Printed the list to view success.

Part 2: Scrape and analyze Mars weather data, which exists in a table.

Used automated browsing to visit the Mars Temperature Data SiteLinks to an external site.. Inspected the page to identify which elements to scrape by using Chrome DevTools.


Created a Beautiful Soup object and use it to scrape the data in the HTML table. 

Assembled the scraped data into a Pandas DataFrame. 

Examined the data types that are currently associated with each column.  int, or float data types. changed and confirmed the data typs for data analysis.

Analysed the data by Using Pandas functions 
How many months exist on Mars?
How many Martian (and not Earth) days worth of data exist in the scraped dataset?
What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
Find the average minimum daily temperature for all of the months.
Plot the results as a bar chart.
Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
Find the average daily atmospheric pressure of all the months.
Plot the results as a bar chart.
About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
Consider how many days elapse on Earth in the time that Mars circles the Sun once.
Visually estimate the result by plotting the daily minimum temperature.
Export the DataFrame to a CSV file.







