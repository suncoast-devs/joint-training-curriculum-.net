# Title

Get your feet wet with SQL and Databases. You will be creating 2 databases for me and writing some simple queries to gather from information. Use your best Judgement for data types the columns should be. 

## Objectives
- Practice Creating, Quering and using SQL databases
- Get your Local Dev set up. 


### Setup

- Download SQL Management Studio
  - https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms
- Download SQL Express 2017
  - https://www.microsoft.com/en-us/download/confirmation.aspx?id=55994

### Explorer Mode

- [ ] Create a database to store Movies
  - [ ] There shoudl be a Movie table with the follow columns: 
      - Id (PK)
      - Title
      - YearReleased
      - Genre
      - Tagline
      - Rating
  - [ ] Create a query that inserts a new Movie
  - [ ] Create a query that Updates all Movies that were  Released in the year 1988 to have a rating of 10
  - [ ] Create a query that Deletes all Movies that are titled "The Neverending Story"
  - [ ] Create a query that finds all horror Movies

- [ ] Create a Database that will store a log of Bank Transactions for an account
  - [ ] This should a table for Transactions with the follow columns: 
    - Id (PK)  
    - Timestamp
    - Action
    - AccountNumber
    - AmountChanged
    - newAmount
  - [ ] Create a query that finds all transaction from Today
  - [ ] Create a query that finds the 10 mist recent transaction for a Given User
  - [ ] Create a query that Inserts a new Item into the table 
  - [ ] Create a query that counts all transactions for a Given Day and given day

  
### Adventure Mode

- [ ] Using SQLCommand, Try to query your database from a C# program. Try to implement the logging from your bank App to log into the database instead of a file. This a preview for Thursday topic. 

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
  
For SQL only Assignments, Add `.sql` containing your queries to your repo. 


## Additional Resources
- https://blog.hubspot.com/marketing/sql-tutorial-introduction
- https://technet.microsoft.com/en-us/library/bb264565(v=sql.90).aspx

