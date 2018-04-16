# LET's GET READY TO RUMBLE!

 Today, you will be working with EF to model connecting data and to simulate joins.  
 
 Problem: 
 Julia is in charge of the local Bocce Ball League. She needs a database to keep track of the teams, players and games that have been played in the league. You need to design this database for her. 


Your database will need to store the following data: 
    Games
        - Home Team
        - Away Team
        - Home Score
        - Away Score
        - Date Happened
        - Notes
    Teams
        - Mascot
        - Color
    Players
        - FullName
        - Nickname
        - Number
        - Position


## Objectives
  - Practice Setup for EF
  - Practice Using EF to work with a database
  - Learn about JOINS with EF
  - All your queries will be in LINQ

### Explorer Mode

  - All the queries should run and the program should build. 
  - All Queries should be using LINQ
  - Put all queries in `Main` in `Program.cs`

- [ ] Set up the Schema using POCOS
- [ ] Show the user the following: 
    - [ ] All the teams, with their win/loss record
    - [ ] All the Players and what team they are on
    - [ ] All the Upcoming games (games who Date Happened is in the future)
    - [ ] Past games
 

#### Tips
    - feel free to create a few methods that add fake data into the database
    - Use SSMS to verify that the data you are entering is correct
    - when creating new items, take note on the relationships

### Adventure Mode
- [ ] Allow Julia( the user) to create new players, and add them to a team
- [ ] Allow Julia to create new teams
- [ ] Allow Julia to schedule games only in the future
- [ ] Allow Julia to enter in the score of a game(only in the past)

### Epic Mode

- [ ] Add the ability to record player stats for each game
- [ ] add the ability to keep track of seasons, not only games

## Turning In

Your homework will be assigned to you via `issues` on your `assignments` repository. Once you are complete with your assignmnet, link the new repo here.



## Additional Resources 
- https://msdn.microsoft.com/en-us/library/aa937723(v=vs.113).aspx
- https://github.com/TIY-NET-Tampa/Lecture-Examples/tree/master/week-6/IntroToEntityFramework/IntroToEntityFramework


## Commands to consider
-- `Install-Package EntityFramework`
-- `Enable-Migrations`
-- `Add-Migrations CreatedTable`
-- `Update-Database`