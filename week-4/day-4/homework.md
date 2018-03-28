# Geopardy

Using this service for your data, http://jservice.io/, build a Jeopardy clone called Geopardy. First we will build the board and a one player game. After you get the basic mechanics, then worry about adding players



## Objectives

### Explorer Mode

- [ ] Display the questions and categories for 5 catgories in a Jeopardy style board (like this: https://lh3.googleusercontent.com/En2ljfur6ALCylFQ8cs6cG99TRvbH7sZDpl0gMsqsZXRk30FWJYcJjjedcW_WXcyw9PDcXVCyc1jSYU-KAn67w-udoY4gkeqqis8iuNc76AC-nxfO0no4FUPIFXW6jIOD55yJGgc) 
- [ ]  When a user clickes on a question, hide the board, and display the question. and allow the user to the type in a answer
- [ ]  If they get the answer correct, add it to a score
- [ ]  After the question is asked, they shoudl no longer be able to click on that square
- [ ]  After all the questions have been asked, the game should have a reset button that gets 5 new random categories
- [ ]  It should look like a Jeopardy board, though i am not expecting anything crazy
 
### Adventure Mode

- [ ] Add player 2 and player 3
- [ ] Add 3 random daily doubles
- [ ] Add double Geopardy round
- [ ] Add a final Geopardy round


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




## Tips and Tricks
- Break down the problems, one at a time, do not try to do too much at one time
- Remember, You can add properties to JavaScript Objects on the fly
- `ng-show` and `ng-hide` are your friends 


