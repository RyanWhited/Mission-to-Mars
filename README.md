# Mission_to_Mars_Challenge
## Overview
Building upon a successful web scraping website that gathers the latest news, images, and facts about Mars, the challenge was to adjust the current web app to include all four of the mars hemisphere images from another website. To do this I used BeautifulSoup and Splinter to scrape full-resolution images of Mars’s hemispheres and the titles of those images, stored the scraped data on a Mongo database, use a web application to display the data, and altered the design of the web app to accommodate these images.

## Results

### Deliverable 1: Scrape Full-Resolution Mars Hemisphere Images and Titles

Created a list and utilized a for loop to collect and store the images and titles into MongoDB.

![Deliverable 1 Code](https://github.com/RyanWhited/Mission-to-Mars/blob/main/README_Images/deliverable-1.png)

### Deliverable 2: Update the Web App with Mars’s Hemisphere Images and Titles

Created a new dictionary in the data dictionary to hold a list of dictionaries with the URL string and title of each hemisphere image. 

![Deliverable 2 Code](https://github.com/RyanWhited/Mission-to-Mars/blob/main/README_Images/deliverable-2(1).png)

Created a function that scrapes the hemisphere data and returns the scraped data as a list of dictionaries with the URL string and title of each hemisphere image.

![Deliverable 2 Code](https://github.com/RyanWhited/Mission-to-Mars/blob/main/README_Images/deliverable-2.png)

Modified the index.html file to access the database and retrieve the img_url and title while looping through the dictionary in the database using {% for hemisphere in mars.hemispheres %}.

![Deliverable 2 Code](https://github.com/RyanWhited/Mission-to-Mars/blob/main/README_Images/deliverable-2(2).png)

### Deliverable 3: Add Bootstrap 3 Components

Modified the container by changing the color and the style of the scraping button.

![Deliverable 3 Code](https://github.com/RyanWhited/Mission-to-Mars/blob/main/README_Images/deliverable-3(1).png)

Resized and rearranged the Mars hemisphere images.

![Deliverable 3 Code](https://github.com/RyanWhited/Mission-to-Mars/blob/main/README_Images/deliverable-3(2).png)

Used the DevTools to test the responsiveness of the website and appeared to function well with other devices.

![Deliverable 3 Code](https://github.com/RyanWhited/Mission-to-Mars/blob/main/README_Images/deliverable-3(3).png)





 
     
