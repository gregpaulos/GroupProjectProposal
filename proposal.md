# Group Project Proposal

### Group Members
* Zackary Moore
* Greg Paulos
* Landon Folkers
* Michael Schreier

### Project Description
Every restaurant has a margarita on the menu. Most of them are terrible. You are in dire need of one that's not. How do you find it? That's where Margarita*finder comes in... 

### Problem statement
I want a margarita, and I need a way to find it efficiently. I would like to find one 
nearby. I would also like to sort my choices by quality or price.

### How will your project solve this problem?
Our project will enable a user to find margaritas nearby. It will allow the user to query by criteria. If they find a great margarita, they can share information about it on margarita*finder. 

### Map the user experience
* Essential
    * As a user, I want to find five options to have a margarita nearby so that I can decide where to go.
    * As an alcoholic, I need to find the closest margarita nearby, so I don't waste my drinking time.
    * As a user, I want to see the results on a map, so that I can know how to get there.
    * As a working professional, I want to find a location for a margarita on my desktop from work, so I can get get a specific drink with my co*workers.
    * As a user, I want to add new location for a margarita, so that others can find it.
    * As an opinionated person, I want to give a star rating on a margarita I drank so that I can have my voice be heard.
    * As a beverage connoissier, I need to find the highest rated margarita nearby, so that I don't waste my money on lower quality margaritas .
* Desirable
    * As an opinionated person, I want to leave a text review of a margarita I drank  so that I can have my voice be heard.
    * As an alcoholic, I need to find the cheapest margarita nearby, so I don't waste my drink money.
    * As a tourist, I want to find five options for a nearby margarita so that I can have one in an unfamiliar city.
* Probably Out of Scope
    * As a bar owner, I want my margarita to be featured on this site so I can attract more customers.
    * As a visual person, I want to post a picture a margarita I am drinking so that I can impress my friends.
    * As a working professional, I want to find a bar that serves food in addition to margaritas so that my co*worker stops complaining about being hungry.


### What technologies do you plan to use?
* Front-End:
    * React (but not redux)
    * Deployment - Firebase (designated team*mate builds and deploys)
    * Library - google maps
* Back*end:
    * Node
    * Express
    * Knex
    * Postgresql
    * Deployment - heroku
* Possible APIs to use info from:
    * Zomato (free 1000/calls per day)
    * Google Places
    * Locu (need to pay)

##### Bonus - Development approaches:
* pair-programming
* we need to take notes from one inclusive meeting a day
* Deploy early and often on front and back end
* Front end: if (window.location "local") then local db else "heroku"
* Back end: process.env ? dev : prod
* Git workflow
    * Branch for each feature
    * "Feature" being a complete user story
    * The main branch always has fully working code.


