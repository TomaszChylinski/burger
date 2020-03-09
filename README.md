# TC-Eat-Da-Burger

### Overview

Using mSQL, Node, Express, Handlebars and a homemade ORM the TC-Eat-Da-Burger is a restaurant application that lets users input the names of burgers they'd like to eat. Once a burger name is entered a user is able to devour it the created burger. Using mySQL the status of each burger will be stored. 

this application creates a user interface that scrapes https://www.nytimes.com/section/technology. The application pulls up to date information including headlines, summaries, links for the top latest articles nytimes/technology has to offer.

### How To Access:

 -- Locally

To download the application onto your own machine please use https://github.com/TomaszChylinski/news-thats-fit-to-scrape.git.

* Once cloned onto your machine, open the terminal of your choice to the following directory news-thats-fit-to-scrape.
* Run npm install (installs all dependecies)
* In your mongo terminal create news-that-fit database
* Run npm start to start the application locally
* Visit your localhost please keep attention to the port you are using


<img src="./public/assets/images/news-that-fits-1.PNG">

-- Online

Please visit www.heroku.com (update link once its up on heroku)

# How to scrape for new articles

* If starting off from a blank database, the user will see a blank page before they scrape for articles


<img src="./public/assets/images/news-that-fits-2.PNG">

* The user may initalize the scrape by clicking on "Get New Articles" found on the top nav



<img src="./public/assets/images/news-that-fits-3.PNG">

* Once clicked the magic behind the scenses will kick off. This process might take a few seconds, once complete the user will be taken to the scrape page where upon a succeessful scrape they will be informed. 


<img src="./public/assets/images/news-that-fits-4.PNG">

* Now once the user redirects themselves back to http://localhost:3000/ they will now see their updated articles served up on the page. 

<img src="./public/assets/images/news-that-fits-5.PNG">


Thank you for viewing my TC-Eat-Da-Burger for any question please feel to visit my portfolio <a href="https://tomaszchylinski.github.io/chylinski-tomasz-portfolio/index.html">page</a>