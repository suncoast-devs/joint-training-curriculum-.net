# I Subscribe to Your Theory!

For this week, you will be working on a subscription service site. This site will allow a user to purchase a subscription to a subscription box, like this site: https://hackerboxes.com/. 

We will be working on this site in a "glass down" manner. starting with the HTML, CSS and JavaScript.

This site will be used by the company to allow users to subscribe to the a box.

This site will be used by a company to allow employees of the site to manage subscriptions



## Site Requirements 

-Allow guest to subscribe to boxes:
    - the site should display all the boxes availible to subscribe to. Each box should have its own page showing the details and example boxes.
    - As a guest I can sign up for box. This should take me a new page that allows me to subscribe to the box. When a user signs up for a box, they get a confirmation number. This does not mean that users will have an account. 
    - When a guest signs up for a box, they enter their name, phone, email, address. All the fields are required. 
- Allow employees to see and manage subscriptions and products. These should be authenticated users, the traditional sense. They should be able to sign up, and log in (can be the same or different pages)
- This should be 2 pages, one for managing subscriptions, and one for managing products

 

# Explorer
*Since we are starting with a glass down approach, tonight is creating the html & css and starting with the javascript*

- [ ] Fork this repo and use it as your base https://github.com/mdewey/StarChart
    - change the connection string, and run `Update-Database`
    - Feel free to rename the solution and project to something more meaningful. 
- [ ] Using angular routing and bootstrap, create the pages that are needed. This includes:
    - [ ] Dashboard
    - [ ] Sign Up for Subscription
    - [ ] Log in/Sign up as employee
    - [ ] CRUD Subscriptions
    - [ ] CRUD Products

*TIPS & TRICKS*
- Unless you are feeling adventurous, Use Bootstrap as a style guide. 
- Drawn out each page before coding it, then code up your drawing
- Use Dummy data in the html for now
- Do not add any JavaScript Functionality during the first pass, get it looking decent using CSS & Bootstrap, then go from there. 


# Adventure
*This will look alot like tomorrow nights explorer mode*

- [ ] Start Designing out the APIs needed to support your UI
- [ ] start creating the controllers, the objects in scope and making the html dynamic 
- [ ] Create an angular service that talks to the your API. This should just a place holder with some empty methods
- [ ] Add a toggle the menu that only shows the `Manage Subscriptions` and `Manage Products` for signed in users 
- [ ] Add deeper JavaScript functionality for other pages. Do no code up any APIs yet

# Epic
- [ ] Take liberties with the UI and create that uses material design

