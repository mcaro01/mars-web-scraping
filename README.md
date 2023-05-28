# mars-web-scraping

![image](https://github.com/mcaro01/mars-web-scraping/assets/125619215/89a2d115-ba09-4c51-a6ee-4ef4fc4ec942)

## Overview:

This new assignment consists of two technical products.  

     Part 1: Scrape titles and preview text from Mars news articles.

     Part 2: Scrape and analyze Mars weather data, which exists in a table.

## Part 1: Scrape Titles and Preview Text from Mars News

Used automated browsing to visit the Mars news site Links to an external site. 

Created a Beautiful Soup object and extracted text elements from the website.

Extracted the titles and preview text of the news articles scraped. Stored the scraping results in Python data structures as follows:

Stored each title-and-preview pair in a Python dictionary. Each dictionary has two keys: title and preview. 

Using Splinter, an automated browsing was used to visit the Mars news site. Then, extracted the HTML code with Beautiful Soup. After that, Inspected the page to 

identify which elements to scrape by using Chrome DevTools.

Extracted the titles and preview text of the news articles and stored them in a dictionary.

Stored all the dictionaries in a Python list.

Printed the list to view success.

         #{'title': "NASA's MAVEN Observes Martian Light Show Caused by Major Solar Storm", 
         #'preview': "For the first time in its eight years orbiting Mars, NASA’s MAVEN mission witnessed two different types of 
         #ultraviolet aurorae simultaneously, the #result of solar storms that began on Aug. 27."}


## Part 2: Scrape and analyze Mars weather data, which exists in a table. (6 parts)


     1)Used automated browsing to visit the Mars Temperature Data SiteLinks to an external site.. Inspected the page to identify 
          which elements to scrape by using Chrome DevTools.

     2)Created a Beautiful Soup object and use it to scrape the data in the HTML table. 

     3)Assembled the scraped data into a Pandas DataFrame. 

     4)Examined the data types that are currently associated with each column.  int, or float data types. 
          changed and confirmed the data typs for data analysis.

     5)Analysed the data by Using Pandas functions 
          a)How many months exist on Mars?
                12
          b)How many Martian (and not Earth) days worth of data exist in the scraped dataset?
               1867
          c)What are the coldest and the warmest months on Mars (at the location of Curiosity)? 
                    
   ![image](https://github.com/mcaro01/mars-web-scraping/assets/125619215/a42a7851-913f-44cd-8455-12092a05415d)

          
                    Find the average minimum daily temperature for all of the months.
                         (0.5, 1.0, 'Daily minimum temperature')
                     Plotted the results as a bar chart.
   ![image](https://github.com/mcaro01/mars-web-scraping/assets/125619215/2dac01fc-c2f3-44dc-af35-23e083b72bb6)

     6)Which months have the lowest and the highest atmospheric pressure on Mars?
               On average, the third month has the coldest minimum temperature on Mars, and the eighth month is the warmest.
               But it is always very cold there in human terms!
        
                    Find the average daily atmospheric pressure of all the months.
                               Atmospheric pressure is, on average, lowest in the sixth month and highest in the ninth.

                    Plotted the results as a bar chart.
 ![image](https://github.com/mcaro01/mars-web-scraping/assets/125619215/7a58abd2-cce6-453c-9cbb-01993b61e1a4)


     #7)About how many terrestrial (Earth) days exist in a Martian year?
          The distance from peak to peak is roughly 1425-750, or 675 days. A year on Mars appears to be about 675 days from the plot. Internet search confirms                 that a Mars year is equivalent to 687 earth days.

                    # Plotted the daily minimum temperature.


![image](https://github.com/mcaro01/mars-web-scraping/assets/125619215/d940463f-bf3f-4205-81af-04af6ee95795)


The DataFrame was exported to a CSV file.







