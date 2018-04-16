# Library API!

The local library wants to modernize how they let people check out books. They need you to build an API. 

The data model includes: 


Books: (A Book's Info)
  - Id
  - Title
  - Year Published
  - Condition
  - AuthorId 
  - GenreId
  - ISBN
  - IsCheckedOut
  - DueBackDate

Author :( Who wrote the book)
  - Id
  - Name
  - Born
  - Died

- Genre: (Book Genre)
  - Id
  - DisplayName

CheckOutLogs (Log of all books that are checked out)
  - Id
  - BookId
  - Timestamp
  - BookCopyId
  - EmailOfPerson
    


## Objectives
- Practice Modeling data
- Practice Creating an API

### Explorer Mode

The library wants an API that enables: 

- [ ] Searching for Book based on title, author, or genre
- [ ] Add a new Book
- [ ] Add a new Author
- [ ] Search for a book based on Checked In Status
- [ ] Check Out a book
- [ ] Check in a Book



### Adventure Mode
- [ ] Update the data model to account for multiple copies of the same book (update the Book to CheckOutLogs to from a `1 to Many ` to a `Many to Many`)
- [ ] Add Library Card Holders that have to sign in to use the API

### Epic Mode
- [ ] Add an API Key system to your API
- [ ] Create an angular Frontend that a library could actually use  


## Turning In

Your homework will be assigned to you via `issues` on your `assignments` repository. Once you are complete with your assignmnet, link the new repo here.


## PRO Tips: 

- Plan. Plan. Plan. Before you create 1 line of code, design out what end points you have in your API and your Database should look like. This will give you a basic plan to follow as you go. 
- KIS(S). Keep Is Simple (Stupid). Work on only 1 endpoint at a time, and focus on what you are doing
- Data is awesome, but not the primary focus of this assignment. Only enter in a little data as possible. 
