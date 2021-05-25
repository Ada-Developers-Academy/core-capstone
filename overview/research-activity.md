# Stack Research Activity

To help you get more experience with the idea of a tech stack and how different pieces of technology are selected and fit together to create a cohesive whole for a given project, we'll be doing a Read & Report exercise.

## Instructions

### Research

In this Read & Report exercise you will collaborate with your group to assign one or two particular technologies from the stack to each group member. Afterwards everyone will research their assigned technologies and try to learn the following:

* What is it?
  * What is its role and responsibility in a tech stack?
  * Why would you use this technology?
  * What are some example use cases of this technology?
* How does it fit in within a tech stack?
  * What does this technology interact with?
  * What interface does the technology present to other technologies (aka _how_ does it interact with other technologies?)?
* What constraints does the technology place on the rest of the stack?
  * How does this technology compare to other similar technologies?
  * Do you need to pay to use this?

#### Example: **PostgreSQL**

* Its role is to provide relational data storage.
* It presents an interface that uses the SQL language for communicating queries to, and data from, the database.
* One of the constraints it places on the rest of the stack is that it must be hosted on a server that is accessible to all other parts of the tech stack that will use the database.

#### Example: **Stripe**

* Its role is to provide a service for managing everything related to real-money payments.
* It presents a RESTful, JSON Web API for communicating with its external service.
* Stripe has a number of different SDKs which are designed to work for web, mobile, and other use cases.
* This service costs money

### Presentation

Once everyone has researched their assigned technologies your group will come together again to discuss how each technology in the stack integrates with the other technologies and plan out how to present what is contained in the tech stack to the rest of the class.

Your group will need to create presentation slides using Google Slides (details will be provided by your instructor). On your slides you should present an overview of the tech stack as a whole and also dive into the major technologies being used.

## Example Tech Stacks

1. The Emerald City
    * Front-end: Vue.js (JavaScript)
    * Back-end: Spring Boot (Java)
    * Database: mySQL
    * Additional Services:
        * Google App Engine
2. The Gamer
    * Unity (C#)
    * Additional Tools:
        * Unity Asset Store
3. The Bandit
    * Front-end: iOS (Swift)
    * Back-end: Django (Python)
    * Additional Tools:
        * XCode
4. The Skateboarder
    * Front-end: Android (Kotlin)
    * Back-end: Firebase Cloud Functions (JavaScript)
    * Database: SQLite
    * Additional Tools:
        * Android Studio
5. The Carpenter
    * Front-end: React.js
    * Back-end: Flask (Python)
    * Database: Firebase Cloud Firestore
    * Additional Services:
        * Amazon Elastic BeanStalk or Amazon RDS
6. The Visionary
    * Front-end: p5.js
    * Back-end: Ruby on Rails
    * Additional Data:
        * External Data Source(s) (Ex: Seattle Food Inspection Database)
        * External API(s) (Ex: Indeed API, Google Maps API)
        * Web Scrapers (Ex: Nokogiri)
