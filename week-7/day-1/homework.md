  # Welcome to SQL!

  Get your feet wet with Entity Framework. You will be creating 2 databases for me and writing some simple queries to gather from information. Use your best Judgement for data types the columns should be. You should not write a single line of raw SQL for this. All of your schema and queries will be in C#.  

  ## Objectives
  - Practice Setup for EF
  - Practice Using EF to work with a database


  ### Explorer Mode


  - Each of the databases should be in their own Solution.
  - All the queries should run and the program should build. 
  - All Queries should be using LINQ
  - Put all queries in `Main` in `Program.cs`

  - [ ] Create a database to store Movies
    - [ ] There should be a Movie table with the follow columns: 
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

  - [ ] Refactor your Morse Code Program to use to a database instead of files. This should use EF to interact with the database. 


  ### Epic Mode

  - [ ] Refactor your University of PROforma to use EF. 


  ## Turning In

  Your homework will be assigned to you via `issues` on your `assignments` repository. Once you are complete with your assignmnet, link the new repo here.

  For this assignment, Put each of the projects in their own git repo and link both of them here. 


  ## Additional Resources 
  - https://msdn.microsoft.com/en-us/library/aa937723(v=vs.113).aspx
  - https://github.com/TIY-NET-Tampa/Lecture-Examples/tree/master/week-6/IntroToEntityFramework/IntroToEntityFramework


  ## Commands to consider
  -- `Install-Package EntityFramework`
  -- `Enable-Migrations`
  -- `Add-Migrations CreatedTable`
  -- `Update-Database`