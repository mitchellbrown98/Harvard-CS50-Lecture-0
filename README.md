# ENGO551-Lab0

This project is the first lab in the ENGO 551 course. I have created a website consisting of 4 pages. A landing page,
an 'About me' page, an 'Art' page, and a 'Projects' page. The site is responsive, so it is mobile friendly and will adjust
the content to the viewport size. 

index.html:
This file is the landing/home page of the site. It contains a header with the website name, and I am using
bootstrap buttons to navigate between pages. 

about.html
This file is the 'About me' page. It contains the bootstrap navigation buttons, some text about myself and what I 
enjoy doing, and 4 columns that were created using bootstrap's grid model. The columns contain some text. 

art.html
This file is the 'Art' page, which is one of my interests. This contains the bootstrap navigation buttons, some text, 
a list of each section on the page - which are also links that can take you straight to each section on the same page. 
There are 3 sections. Each section has a title, an image, and some short information about the image. The information text
also contains external links for more information - which open a new tab when clicked. At the bottom of the page there is 
another link to bring you back up to the top of the page. 

projects.html
This file is the 'Projects' page. It contains 2 columns. The first is about my small business, which has a screenshot
image of our website, some information about the business, a table with some information about the business for each year 
of operation, and a button to take you to the business website, which opens it up in a new tab. The 2nd column contains some
information about an independant project I am working on. I am using the leaflet and ESRI plugins here to provide a simple
demonstration of what my project will do. The page will request your location to perform the demonstration. If you deny the
request, you will get a popup error message. Accepting the request will place a bike icon, along with some info on the map
at your geolocation. 

styles.css
This file is my stylesheet, which I have used to include different CSS properties and selectors, change my font and text
sizes, create containers, use the #id selectors, and the .class selectors. I have also added mobile-responsive media queries
here to adjust my image sizes and container sizes when viewing the website on a smaller screen.

variables.css
This file is the 2nd stylesheet, created from variables.scss

variables.scss
This file is an SCSS, where I have declared some color variables for use in my bootstrap grid model on the art.html page.

Image files:
bikeicon.png
detailing.png
headshot.jpg
img1.PNG
img2.PNG
img3.PNG