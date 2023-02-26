# mars_web_scraping
Mars News &amp; Mars Weather Data <br>
Web Scraping Challenge <br>
Part 1: Scrape Titles and Preview Text from Mars News <br>

1. Inspect https://static.bc-edx.com/data/web/mars_news/index.html and identify title and preview text elements<br>
2. Create Beautiful Soup object to extract elements from the website<br>
3. Extract and store data in a list<br>

Part 2: Scrape and Analyze Mars Weather Data<br>
1. Inspect https://static.bc-edx.com/data/web/mars_facts/temperature.html and identify title and preview text elements<br>
2. Create Beautiful Soup object to extract elements from the website<br>
3. Scraped data into Pandas DataFrame <br>
4. Convert data to appropriate data types <br>
5. Analyze the dataset and answer the following questions: <br>
  - How many months exist on Mars?<br>
  - How many Martian (and not Earth) days worth of data exist in the scraped dataset?<br>
  - What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:<br>
    a.Find the average minimum daily temperature for all of the months.<br>
    b.Plot the results as a bar chart.<br>
  - Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:<br>
    a.Find the average daily atmospheric pressure of all the months.<br>
    b.Plot the results as a bar chart.<br>
  - About how many terrestrial (Earth) days exist in a Martian year? To answer this question:<br>
    a.Consider how many days elapse on Earth in the time that Mars circles the Sun once.<br>
    b.Visually estimate the result by plotting the daily minimum temperature.<br>
6. Export the DataFrame to a CSV file<br>

