# Mars_Hemisphere
#### *HTML Web scraping on Mars data to create a Flask web application using Python and MongoDB*

## Overview
The purpose of this project is to take the data about the Martian hemispheres and to create pictures of all 4 possible combinations of the hemispheres, after this is done, the urls and titles of the photos are put into a directory and are turned into a list. Using HTML and Python, the data is taken from the Jupyter file and is then turned into a Python file, a scraping function is then created to create a new list of dictionaries to hold the URL as well as the photos of the hemispheres and then return the scraped data as a list of dictionaries with the URL string and title of each hemisphere image. After working with the Mongo database, the index.html file is used to scrape the data and display the 4 hemispheres. Finally, the index.html file is altered to allow it to be mobile friendly as well as create a custom table/chart.

## Resources 
The web pages that I used/scraped are as follows:
  - https://data-class-mars.s3.amazonaws.com/Mars/index.html
  - https://spaceimages-mars.com
  - https://galaxyfacts-mars.com
  - https://marshemispheres.com/
  
The software that I used are as follows:
  - Python
  - Jupyter Notebook
  - Pandas, BeautifulSoup, Splinter, ChromeDriverManager, Flask, PyMongo
  - MongoDB
  - HTML5
  - Bootstrap 3

## Summary
This project produced good quality photos of the 4 hemispheres of Mars, as well as store some extra information about the red planet and compare them with Earth.
