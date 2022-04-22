# Mission-to-Mars

## Overview of the Analysis:

Using BeautifulSoup and Splinter to scrape full-resolution images of Mars’s hemispheres and the titles of those images, store the scraped data on a Mongo database, use a web application to display the data, and alter the design of the web app to accommodate these images.

### Purpose:

#### This new assignment consists of three technical analyses:

-Scrape Full-Resolution Mars Hemisphere Images and Titles

-Update the Web App with Mars Hemisphere Images and Titles

-Add Bootstrap 3 Components


## Resources

**Data Source:** https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars

**Software:** Visual Studio Code, jupyter Notebook, Flask, Splinter, Web Drive Manager, Beautiful Soup, Pymongo, MongoDB, Mongo DB Compass, htmlslib, lxml.

## Results:

#### Using BeautifulSoup and Splinter, scrape full-resolution images of Mars’s hemispheres and the titles of those images:


  -Code is written that retrieves the full-resolution image and title for each hemisphere image.
  
  -The full-resolution images of the hemispheres are added to the dictionary.
  
  -The titles for the hemisphere images are added to the dictionary.
  
  -The list contains the dictionary of the full-resolution image URL string and title for each hemisphere image.
  

##### Using Python and HTML, add the code you created in scraping.py file, update Mongo database, and modify index.html file so the webpage contains all the information collected in this module as well as the full-resolution image and title for each hemisphere image:


  -he scraping.py file contains code that retrieves the full-resolution image URL and title for each hemisphere image.
  
  -The Mongo database is updated to contain the full-resolution image URL and title for each hemisphere image.
  
  -The index.html file contains code that will display the full-resolution image URL and title for each hemisphere image.
  
  -After the scraping has been completed, the web app contains all the information from this module and the full-resolution images and titles for the four hemisphere images.


#### Update web app to make it mobile-responsive, and add two additional Bootstrap 3 components to make it stand out:


  -The webpage is mobile-responsive.
  
  -Two additional Bootstrap 3 components are used to style the webpage.
  
  

## Summary:

#### The Mission_to_Mars_Challenge.ipynb file with all the code used for scraping.

#### An updated scraping.py file.

#### The app.py file.

#### The index.html file in the template folder.

