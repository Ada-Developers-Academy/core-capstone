# Tech Stack Examples

## bEtsy

Here is an advanced bEtsy as an example Capstone Idea:

I want users to be able to use an online e-commerce store to sell the home-made/craft products they have. There will be two kinds of users: guest users and merchants.

Merchants must create an account to list products. They can:

  - manage products
  - manage shipments
  - view a dashboard of their orders and shipments

This project will be on the web. The front-end will be in React, the back-end API will be in Flask. I need to store user data, product data, order data, so I will use Firebase Cloud Storage to store data.

To manage shipments, this project will utilize the USPS API.

For the seed data, I will scrape information from the USPS shipping rate website to find all of the shipping rates for every region. I will use this information for the shipping features in my app.

Users will log on using Facebook OAuth.

I will deploy my front-end on Google App Engine. I will deploy my back-end on Heroku.

## Previous Example

Here is an example of the major technologies used in a previous capstone project:

I want users to be able to track their study schedule. I want users to do this on their phone/the mobile platform. I want to make both an iOS/Android app using the React Native library.

- I will make both an Android and iOS front-end
  * [React Native](https://facebook.github.io/react-native/) (based on [React](https://facebook.github.io/react/))
  * [Moment.js](https://momentjs.com/) date/time library

- I will make a back-end API that is responsible for the scheduling and assignments logic
  * [Node.js](https://nodejs.org/)
  * [Express](https://expressjs.com/) web application server
  * [MongoDB](https://www.mongodb.com/) database

* I will deploy my back-end using Amazon Elastic Beanstalk

# Technologies by Category

## Game Development

* Unity (C#)

## Front-end (Web or Mobile)

How do your users interact with your app?

### Web Platform

*   React.js (JavaScript or TypeScript)
*   Angular.js (JavaScript or TypeScript)
*   Vue.js (JavaScript or TypeScript)
*   P5.js (JavaScript)

### Mobile Platform

*   Android (Java or **Kotlin**)
    *   Instructor note: We highly recommend Kotlin
*   iOS (Swift)
*   Flutter SDK (Dart)
*   [Progressive Web App](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps) (HTML + CSS + JS)

## Back-end

How does your app interact with data, services, logic, and the front-end?

*   Flask (Python)
*   Django (Python)
*   Express (Node.js)
*   Firebase Cloud Functions (JavaScript)
*   Rails (Ruby)
*   Spring Boot (Java)

## Full-stacks

Do you have an app with a full-stack framework that deals with the front-end and the back-end in the same code base?

*   Django (Python)
*   Rails (Ruby)

## Data stores

Does your app need to persist any data? What kind of data does it need to store? How will you persist that data?

*   Firebase Cloud Firestore
*   PostgresQL
*   MongoDB
*   SQLite
*   MySQL/MariaDB

## Tools

### External APIs to leverage

Does your app need to use an external service/API to get some data?

Examples:
*   Google Maps API for location data
*   Yelp API for restaurant review data
*   Eventbrite API for local event data
*   And so much more!

Things that you must ask when confirming your external APIs:

- Have you found the documentation that proves you get the data you want from a specific end point?
    - (For example, if your project needs information about allergies in restaurants, does the Yelp API _actually_ have an allergy endpoint? All projects need to confirm this before using the API)
- Does this API cost money?
- How does this API give API keys? (Do you need to request an API key?)

### Web Scrapers

Does your app need to scrape a website? Maybe there's information you need from an online encyclopedia. How can you write a script to grab all of the important data you need?

*   Nokogiri
*   Beautiful Soup

### External Data Sources to leverage

Does your app need seed data? Where are you getting this seed data?

(What spreadsheets will you read? What websites will you scrape?)

### Authentication

Does your app need to persist user data? If yes, then your app needs to have user log-in as a feature. We encourage using one of the following options.

- Firebase Authentication
- OAuth
    *   Facebook
    *   Twitter
    *   Google
    *   GitHub

## Deployment Technologies

You will need to look up options on how to deploy your front-end, back-end, components, things, etc.

Mobile front-ends and non-web tech stacks will have specific deployment instructions

*   Heroku
*   Docker, with additional deployment on a different service
*   Amazon EBS
*   Amazon RDS
*   Google Cloud Services
    *   AppEngine
    *   CloudSQL
    *   Cloud Functions
    *   Cloud Storage

## Our Recommended Off-The-Menu Tech Stacks

1. The Emerald City
    - Front-end: Vue.js (JavaScript)
    - Back-end: Spring Boot (Java)
    - Database: mySQL
    - Additional Services:
        - Google App Engine
2. The Gamer
    - Unity (C#)
    - Additional Tools:
        - Unity Asset Store
3. The Bandit
    - Front-end: iOS (Swift)
    - Back-end: Django (Python)
    - Additional Tools:
        - XCode
4. The Skateboarder
    - Front-end: Android (Kotlin)
    - Back-end: Firebase Cloud Functions (JavaScript)
    - Database: SQLite
    - Additional Tools:
        - Android Studio
5. The Carpenter
    - Front-end: React.js
    - Back-end: Flask (Python)
    - Database: Firebase Cloud Firestore
    - Additional Services:
        - Amazon Elastic BeanStalk or Amazon RDS
6. The Visionary
    - Front-end: p5.js
    - Back-end: Ruby on Rails
    - Additional Data:
        - External Data Source(s) (Ex: Seattle Food Inspection Database)
        - External API(s) (Ex: Indeed API, Google Maps API)
        - Web Scrapers (Ex: Nokogiri)