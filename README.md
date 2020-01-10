# NOMSTER WEB APPLICATION

This web application is a Yelp clone that functions as a platform for users to share their personal opinion about their experience at different places. A signed up user can enter the name, address, an image and description of a place then include a comment about the place and a rating. In addition, other people who view the page can also leave comments, sharing their sentiment about that place. The application integrates with the Google Maps API and includes features like user comments, star ratings, image uploading, and user authentication.

![Nomster main page](/app/assets/images/nomstermainpagescreenshot.png)


## Tools used during the Application Development include

Ruby on Rails. Ruby version 2.5.3 and rails version 5.2.3

jQuery

HTML and CSS

Git 

GitHub

Heroku

Will_paginate gem 

Geocoding API

Amazon Web Services-Amazon S3

Mailer

SendGrid

## Creating and Running the application

Set up the initial project structure by creating a new rails web application that uses Postgresql and create an initial, empty database by running rake db:create to have a place to store information. Start the server. Construct the web development pipeline: git, github and heroku. This will save and run the application code in the development and production environment. 

Set up models and database, build the infrastructure which includes controllers, routes tables and view files. Set up the pipeline for uploading images to the web application using Amazon S3 as the Uploader that stores images. Add carousel image slider that enables images slideshow on a homepage that has multiple images in it. Apply user authentication by setting up the devise gem and adding login links to the navbar. This grants users ability to sign up, sign in and sign out of the application. 

Incorporate the will_paginate gem to the web application to facilitate the display of hundreds or thousands of places on a page. Integrate Google Maps in the application by using a geocoding API to convert the addresses into numerical floating numbers, the latitude and longitude. Pin the desired latitude and longitude. Finally display the map on a detail page of the application. 

The above features will allow logged in users to create names, addresses, images, descriptions, comments and ratings for various places. Subsequently, viewers who see the page can also leave their comments.

Generate a mailer to send automated emails to the user who created a place after someone/ a viewer leaves a comment for it. Configure the web application to work with SendGrid, a production mail server that sends notification emails on the production environment, Heroku.  

Style the pages using HTML and CSS.

Continuously save the code by pushing it to GitHub and showcase the application in production by pushing it Heroku.


## View the application in the link provided below

[NOMSTER](https://nomster-dessy-owiti.herokuapp.com/)

