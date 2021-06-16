# Tech Stack Examples

A tech stack is a combination of technologies that run software. Every project runs and is deployed using more than one technology.

For your capstone project, you will need to choose a collection of technologies that will comprise the tech stack for your application. The specific technologies you choose depends on your goals and personal interests.

When choosing a set of technologies, it can be helpful to think of it like putting together a puzzle. Each technology fits into a particular location in the stack, and it usually integrates with one or more other technologies in the stack. Think about what technologies have been used in your previous projects and how each of them have interacted with the other technologies.

Here is a document with a list of different technologies. This list should **_inspire_** you.

This is not an exhaustive list of possible technologies to use. This isn't a required list of possible technologies to use. This is a resource to help you continue your research and help you make informed decisions.

There are two sections in this document:

- A list of technologies by use-case category
- A list of example tech stacks

## Technologies by Category

### Game Development

- Unity (C#)

### Front-end (Web or Mobile)

How do your users interact with your app?

#### Web Platform

- React.js (JavaScript or TypeScript)
- Angular.js (JavaScript or TypeScript)
- Vue.js (JavaScript or TypeScript)
- P5.js (JavaScript)

#### Mobile Platform

- Android (Java or **Kotlin**)
  - Instructor note: We highly recommend Kotlin
- iOS (Swift)
- Flutter SDK (Dart)
- [Progressive Web App](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps) (HTML + CSS + JS)

### Back-end

How does your app interact with data, services, logic, and the front-end?

- Flask (Python)
- Django (Python)
- Express (Node.js)
- Firebase Cloud Functions (JavaScript)
- Rails (Ruby)
- Spring Boot (Java)

### Full-stacks

Do you have an app with a full-stack framework that deals with the front-end and the back-end in the same code base?

- Django (Python)
- Rails (Ruby)

### Data stores

Does your app need to persist any data? What kind of data does it need to store? How will you persist that data?

- Firebase Cloud Firestore
- PostgreSQL
- MongoDB
- SQLite
- MySQL/MariaDB

### Tools/Utilities/Resources

#### External APIs to leverage

Does your app need to use an external service/API to get some data?

Examples:

- Google Maps API for location data
- Yelp API for restaurant review data
- Eventbrite API for local event data
- And so much more!

Things that you must ask when confirming your external APIs:

- Have you found the documentation that proves you get the data you want from a specific end point?
  - (For example, if your project needs information about allergies in restaurants, does the Yelp API _actually_ have an allergy endpoint? All projects need to confirm this before using the API)
- Does this API cost money?
- How does this API give API keys? (Do you need to request an API key?)

#### Web Scrapers

Does your app need to scrape a website? Maybe there's information you need from an online encyclopedia. How can you write a script to grab all the important data you need?

- Nokogiri
- Beautiful Soup

#### External Data Sources to leverage

Does your app need seed data? Where are you getting this seed data?

(What spreadsheets will you read? What websites will you scrape?)

#### Authentication

Does your app need to persist user data? If yes, then your app needs to have user log-in as a feature. We encourage using one of the following options.

- Firebase Authentication
- OAuth
  - Facebook
  - Twitter
  - Google
  - GitHub

### Deployment Technologies

You will need to look up options on how to deploy your front-end, back-end, components, things, etc.

Mobile front-ends and non-web tech stacks will have specific deployment instructions

- Heroku
- Docker, with additional deployment on a different service
- Amazon EBS
- Amazon RDS
- Google Cloud Services
  - AppEngine
  - CloudSQL
  - Cloud Functions
  - Cloud Storage

## Our Recommended "Off-The-Menu" Tech Stacks

The following is a list of combined tech stack "sandwiches." If you'd like to choose a "pre-made" tech stack, feel free to use any of these tech stacks.

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
