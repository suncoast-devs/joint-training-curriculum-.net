# University of PROforma

You are tasked with making a database diagram, database, and 2 console applications 

The database will have _at least_ the following entities, and the following columns: 

- Courses
  - Number
  - Level
  - Name
  - Room
  - Start Time

- Professors
  - Name
  - Title (Mr/Ms/Dr, etc...)
  
- Students
  - FullName
  - Email
  - PhoneNumber
  - Major

The following relationships are true: 
- Courses have at least one Professor
- Students can enroll in course
- Courses have many Students
- Students belong to many Campuses


*NOTE:* You need to add Primary Keys and Foreign Keys to the tables, as well as add any joining needed. 


## Objectives
- Practice working with SSMS and Databases
- Understanding and creating a Database Diagram
- Working with User Input and C#


### Explorer Mode

- [ ] Create a Database Diagram that illustrates the relationships. This should be a picture in the root of your repository
- [ ] Create the Database. I want to see the Create Database script that includes all the tables and relationships

- [ ] Create a "admin" Console app that allows a user to : 
  - [ ] Add Professors
  - [ ] Add Classes
  - [ ] View who is enrolled in a class
  - [ ] View all Classes, who is teaching them, and who is enrolled

- [ ] Create a "student" app that allows a user a to enroll into a class. 
  - [ ] As a user, I should be able to select a course, and type in my information, and be enrolled in that course
  - [ ] Type in my name, and view what course I am enrolled in

### Adventure Mode

- [ ] Add Campuses to your data model as a "Parent" to all entities. Use your best judgement to define relationships
- [ ] Update your data model to allow professors being apart of many campuses
- [ ] Create a "Professors" console app that allows a professor to see who is enrolled in class
- [ ] Add Semesters, and allow a student to select a semesters
- [ ] Refactor your 2 console apps to be in the same solution, and re-use your database access layer 


### Epic Mode
- [ ] Add Student sign in (*DO NOT STORE PASSWORDS AS PLAIN TEXT*)
 
## Turning In

Your homework will be assigned to you via `issues` on your `assignments` repository. Once you are

These steps will be followed for almost every assignment going forward. Once you've completed at` least _explorer_ mode and you're satisfied with your work, let's get it published. First let's get it up on GitHub.

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

Your repository, for explorer mode,  should have three folders: 
- SQLScripts
  - all your SQL scripts to create your database
- AdminConsole
  - the console app for the Admin app
- StudentConsole
  - the console app for the student app



### Additional Code Samples: 
https://github.com/TIY-NET-Tampa/Lecture-Examples/tree/master/week-4/IntroToADONET/ConsoleApp1