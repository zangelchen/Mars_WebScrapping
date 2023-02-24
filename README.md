# Mars_WebScrapping

Taking on a full web-scraping and data analysis project, identify HTML elements on a page, their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. Scrape various types of information including HTML tables and recurring elements, like multiple news articles on a webpage.

This new assignment consists of two technical products. You will submit the following deliverables:
1. Deliverable 1: Scrape titles and preview text from Mars news articles.
2. Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.

Part 1: Scrape Titles and Preview Text from Mars News
Use automated browsing to visit the Mars news siteLinks to an external site. Inspect the page to identify which elements to scrape.
- Create a Beautiful Soup object and use it to extract text elements from the website.
- Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures as follows:
- Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: title and preview. An example is the following:
- Store all the dictionaries in a Python list.


Part 2: Scrape and Analyze Mars Weather Data
Use automated browsing to visit the Mars Temperature Data SiteLinks to an external site.. Inspect the page to identify which elements to scrape. Note that the URL is https://static.bc-edx.com/data/web/mars_facts/temperature.html.
- Create a Beautiful Soup object and use it to scrape the data in the HTML table. Note that this can also be achieved by using the Pandas read_html function. However, use Beautiful Soup here to continue sharpening your web scraping skills.
- Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website. Here’s an explanation of the column headings:
- Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.


How many months exist on Mars?

![image](https://user-images.githubusercontent.com/117549284/221122806-0bc1b563-545d-49b8-a94c-aa03267c42f6.png)

How many Martian (and not Earth) days worth of data exist in the scraped dataset?
![image](https://user-images.githubusercontent.com/117549284/221122818-cc03e45e-bc23-4c31-84f4-3f924dc94f3c.png)

What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
![image](https://user-images.githubusercontent.com/117549284/221122948-53b49454-7d35-4606-a219-f87e46628365.png)

Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
![image](https://user-images.githubusercontent.com/117549284/221122683-4f573082-f483-46b5-b390-6a774371b519.png)

About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
![image](https://user-images.githubusercontent.com/117549284/221122784-eb122ad0-e5ba-46cd-8897-f843e4ac044b.png)



