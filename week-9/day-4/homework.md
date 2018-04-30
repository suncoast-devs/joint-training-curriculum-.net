# So, What do you wanna do tonight?

The City of Acme is looking for page to get to show all the local events. This page should be mimic the functionality of meetup.com. Be sure to look at the requirements for each level and not to get ahead of yourself.

## Objectives
- practice creating Web API 2 endpoints
- Practice angularJS Routing
- Use seed data to handle populating your database

## Rough Data Model to get you started
*NOTE*: The Foreign Keys have been left off

City
    - Id
    - Name

Event
    - Id
    - Title
    - Tagline
    - Long Description
    - Address
    - City
    - State
    - Zip
    - Age Limit
    - Price
    - DateHappening
    
Attendee 
    - Id
    - Email

_Relationships_
a City has many Events
a Event has many Attendees
a Attendee can go to many Events


## Explorer
- [ ] Create the home page that shows a list of events that happening in PROburg. This show include only the event title, short description, date and location for the event
- [ ] A User should be able to search for events based on title, DateHappening, Age Limit
- [ ] A user should be able to click an event and see all details about that event on a new page. This should display everythign about that Event, including all the details and all the Attendees that have registered
- [ ] A user should be able to be able to sign up for an event,on the event detail page,  by providing only an email. This email is required

## Adventure 
- [ ] Implement a wait list if an event gets too many attendees
- [ ] Using Google Maps Web SDk, add a latitude and longitude to the Model and show a location on the map, allow to user to find events near them
- [ ] Add a `EventHost` table, and allow users to search based on event host
- [ ] Allow users to add a new event
- [ ] Add a keyword system and allow users to search by keyword
- 
## Epic
- [ ] Add User Authentication using OAuth. This might be easier to recreate the project and add authentication from the templates
- [ ] Implement more features from meetup.com


## PRO-TIPS
- Remember, only Explorer mode is required. Do not borrow trouble by trying to do more.
- I highly suggest planning. Before writing a line of code, plan out (at least):  
    1) database schema
    2) API Endpoints 
    3) Angular URLs
    4) The UI for Explorer mode
- Git is your friend, commit and push often.
- Work on one area of the site at a time, small chunks are easier to keep in your head at a time.
