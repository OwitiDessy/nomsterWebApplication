# NOMSTER WEB APPLICATION

This web application is a Yelp clone that functions as a platform for users to share their personal opinion about a place. A signed up user can enter the name, address, an image and description of a place then include a comment about the place and a rating. In addition, other people who view the page can also leave comments about their experience at that place. The application integrates with the Google Maps API and includes features like user comments, star ratings, image uploading, and user authentication.

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




## Creating and Running the application

Set up the initial project structure by creating a new rails web application that uses Postgresql and create an initial, empty database by running rake db:create to have a place to store information. Start the server.Construct the web development pipeline: git, github and heroku. This will save and run the application code locally and in production. 

Set up models and database, build the infrastructure which includes controllers, routes tables and view files. Set up the pipeline for uploading images to the web application using Amazon S3 as the Uploader that stores images. Add user authentication by setting up the devise gem and adding login links to the navbar. This grants users ability to sign up, sign in and sign out of the application. 

Incorporate the will_paginate gem to the web application to facilitate the display of hundreds or thousands of places on a page.Integrate Google Maps in the application by using a geocoding API to convert the addresses into numerical floating numbers, the latitude and longitude, then pin the desired latitude and longitude and finally display the map on a detail page of the application. 

The above features will allow logged in users to create names, addresses, images, descriptions, comments and ratings for various places.Subsequently, viewers who see the page can also leave their comments.

Add and enable mailer to send automated emails to the user who created a place after someone/ a viewer leaves a comment for it. 

Style the pages using HTML and CSS.

When finished save the code by pushing it to GitHub and showcase the application in production by pushing it Heroku.


## View the application in the link provided below

[FLIXTER](https://nomster-dessy-owiti.herokuapp.com/)

