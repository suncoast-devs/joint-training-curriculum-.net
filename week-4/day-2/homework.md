# Top Artists

Using the API located here https://www.last.fm/api/show/chart.getTopArtists (you need to make an account with last.fm to get your access key) Create me a page that displays the top artists using angularjs. 

## Objectives
- Work more with angular
- Work more with APIs


### Explorer Mode

- [ ] Create a simple UI that displays the top 50 artist from the Last.fm API. 
- [ ] Create and user a template file for an artist. This template should display the picture that came with the artist, the artist name, as well as the playcount and listencount (its all in the data, trust me)
- [ ] Give it basic styling, but dont go crazy, you have a hackathon to work on

### Adventure Mode
- [ ] Work on your hack-a-thon project 


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

