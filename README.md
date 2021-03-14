# Mission-to-Mars
The purpose of this project was to create a web application that scrapes different web sources for relevant information about Mars.  I used BeautifulSoup to scrape the different Mars data types which included the latest Mars news, the most recent featured image of Mars, a Mars facts table compared to Earth and images of the four hemispheres of Mars.  After scraping, the data was then stored in MongoDB database and then loaded into an HTML file using a Flask template that interfaces with Python for visualization.  Lastly, I formatted and customized the HTML to have a black background, orange and white text and thumbnail style hemisphere images by using Bootstrap and configured the app such that clicking an oragne button on the webpage would re-scrap and load current Mars data.

### Websites Scraped:
-	Latest Mars News:  https://data-class-mars.s3.amazonaws.com/Mars/index.html
-	Featured Mars Image:  https://data-class-jpl-space.s3.amazonaws.com/JPL_Space/index.html
-	Mars Facts:  https://data-class-mars-facts.s3.amazonaws.com/Mars_Facts/index.html
-	Mars Hemispheres:  https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars
