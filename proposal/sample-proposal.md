# Sample Proposal

## Project Proposal - Suzanne Avitus

## Project Name

Parks for Humanity

## Individual/Group

Individual

## Learning Goals

- Practice creating a full stack CRUD application with front-end
- Integrate external web APIs for geographic data
- Integrate external Google Maps controls

## Project Description

There are approximately 343 parks in the City of Seattle! Some are just small slivers of land, and others are vast with miles and miles of trails. Kids or newbies to Seattle need a guide to help them explore all these beautiful parks. 
This application provides a map showing the location of all these parks and links you to the park details. When an explorer visits a park, they can "check off" that park as seen in the app to keep track of their explorations, and win badges.

## Project Type

Full stack web app, primarily targeting mobile users (UI designed to target phone dimensions)

## Main Front-end Technology

- React

## Additional Front-end Technologies

- React Router
- Bootstrap
- Google Maps control

## Main Back-end Technology

- Flask

## Additional Back-end Technologies

- Seattle Parks API

## Other Technologies

- OAuth authentication (stretch goal)

## Database 

- PostgreSQL

## Deployment Technologies

- Front end deployed to Heroku
- Back end deployed to Heroku

## Wireframes

- [Wireframes](https://drive.google.com/drive/folders/1esk8qN2Lwl4Vn7ecCTkKdhQVsIzwtTZS)
- [High-level Wireframe](https://imgur.com/YUvCxY4)

## MVP Feature Set

1.  a user can see a map with point locations of all seattle parks
	- the map point locations will indicate (by color or symbol) whether the user has visited the park yet
	- the user can zoom in and out of the map 
	- the map also shows the user's current location
2.  the user can select a park point location, which navigates to a park details page.
	- if the user is signed in, the park details page shows whether or not the user has been there and a date of visit, if so
3. a user can sign into the app to see their saved data
	- MVP treats any login attempt as successful (for the supplied user name)
	- Stretch goal to integrate authorization using an OAuth library
4. the user has an account details/achievements page
	- the page shows how many parks they have visited
	- the page shows the points or badges earned
5. the user can see a page of general info about the game app (how to use, datasets involved, etc.)
	
 
