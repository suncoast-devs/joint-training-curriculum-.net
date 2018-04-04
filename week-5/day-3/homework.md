# ATM Machine

Create a simple app that lets a user interact with their bank account. This will have relatively intense UI. Remember to try to separate out the logic from the UI using classes and methods. This program will keep track of the checkings and savings account.
(NOTE: Don't worry about security yet)
## Objectives
- work with C# and practice program structure
### Explorer Mode

- [ ] the system assumes only 1 user
- [ ] when the program starts, it will display the current balance for their checking  and savings account. If none exist, show 0. 
- [ ] Ask to do one of the follow transactions 
    - [ ] withdraw from savings, this should prompt the user to enter an amount to withdraw, then remove that amount. This should do some basic error handler (i.e, make sure that the value inputted is a number, that the user has enough funds)
    - [ ] withdraw from checking, this should prompt the user to enter an amount to withdraw, then remove that amount. This should do some basic error handler (i.e, make sure that the value inputted is a number, that the user has enough funds)
    - [ ] deposit to savings , this should prompt the user to add a an amount to this account, then add that amount. This should do some basic error handler (i.e, make sure that the value inputted is a number)
    - [ ] deposit to checking, this should prompt the user to add a an amount to this account, then add that amount. This should do some basic error handler (i.e, make sure that the value inputted is a number)
    - [ ] transfer money from savings to checking, this should prompt the user to enter an amount to transfer, then remove that amount. This should do some basic error handler (i.e, make sure that the value inputted is a number, that the user has enough funds) 
    - [ ] transfer money from checking to savings, this should prompt the user to enter an amount to transfer, then remove that amount. This should do some basic error handler (i.e, make sure that the value inputted is a number, that the user has enough funds) 
- [ ] the system should save the new amount to a file after every action
- [ ] the system should load the current amounts when the program starts
- [ ] the system should log all the transactions that occur to a file, these logs should have `what was done`, `the amount that moved` `when it happened` and `what accounts were affected` and other information you feel is useful


 
### Adventure Mode

- [ ] Add the ability to have multiple users. These users should not be able to see other users accounts totals.  Userss should have a user name and pin number. 
- [ ] Add the ability to have more than 2 accounts. Create a unique account number for each account
- [ ] A User should be able to close their account



### Epic Mode
- [ ] Add interest rates that happen ever so often (For testing, I would start with every second)
- [ ] A User can transfer a money to some one elses account, using either a username or account number
- [ ] Encrypt the files so that only your program can read and write to them


## Setup 
- open `Visual Studio 2017` and create a new `console application` 
- be sure to select `create git repo` and make sure it has a `.gitignore`

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

  The `-u` option tells git we want to making pushing the `master` branch to `origin` the default, so next time, we can just type `git push`.

- Now that our source code is up on GitHub, let's publish our page to [Surge](https://surge.sh). The command to do this has already been setup for you:

  ```sh
  yarn deploy
  ```

Once you are completely, go to the issue on our `assignments` repository, leave the link the repo of your work, and close the issue. I will not know you are down until you close the issue. 

