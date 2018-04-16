# Car Dealership

You are tasked with making a database diagram, database, and a few queries for a local car dealership

The database will have _at least_ the following entities, and the following columns: 

- CarDatas
  - Make
  - Model
  - Year

- Cars
  - Color
  - VIN Number
  - Date Added to Lot
  - AvailableForLease
  - MilesDriven

- Customers
  - FullName
  - Email
  - PhoneNumber
  - FavoredCustomer

- Leases
  - ExpirationDate
  - TotalCost
  - UpFrontPayment
  - CostPerMonth


The following relationships are true: 
- A Lease has One Car
- A Lease can have Many Customers
- A Customer can have Many Leases
- CarDatas have multiple cars


*NOTE:* You need to add Primary Keys and Foreign Keys to the tables, as well as add any joining needed. 


## Objectives
- Practice working with SSMS and Databases
- Understanding and creating a Database Diagram


### Explorer Mode

- [ ] Create a Database Diagram that illustrates the relationships. This should be a picture in the root of your repository
- [ ] Create the Database. I want to see the Create Database script that includes all the tables and relationships
- [ ] Create the following queries: 
  - [ ] Find all non Expired Leases
  - [ ] Select the email of all favored customers
  - [ ] Show me the make, model, color, availability, and Miles Driven for all Cars
  - [ ] All the emails of Customers that have expired leases
  - [ ] The make and Model of the cars that are leased out


### Adventure Mode

- [ ] Using SQLCommand, Try to query your database from a C# program. Try to use this database from a console app. This a preview for Thursday topic. 

## Turning In

Your homework will be assigned to you via `issues` on your `assignments` repository. Once you are

These steps will be followed for almost every assignment going forward. Once you've completed at least _explorer_ mode and you're satisfied with your work, let's get it published. First let's get it up on GitHub.

- First, let's add all our work to git, and ask it to commit it:

  ```sh
  git add .
  git commit -m "My first webpage"
  ```

  Feel free to replace _"My first webpage"_ with a more meaningful message.

- Push our local commits to GitHub:

  ```sh
  git push -u origin master
  ```

The files I am looking for are:
  - A Script to recreate your database and tables
  - A Script for each of the queries.
   

For SQL only Assignments, Add `.sql` containing your queries to your repo. 

