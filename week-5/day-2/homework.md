# Morse Code Converter

Create a simple app that lets a user type in a phrase in english and print out the phrase in Morse Code

## Objectives

### Setup
- [ ] download and use this csv https://raw.githubusercontent.com/mdewey/morse-code/master/morse.csv


### Explorer Mode

- [ ] The program should read the conversion data from a file and build a `Dictionary` in memory to help in the conversion
- [ ] As a user, I should be able to type in a phrase to convert. This should include letters and numbers
- [ ] The Program should convert the text that the use typed in to Morse Code
- [ ] The Program should display the converted text to the user
- [ ] The Program should ask user if they have another word convert, if yes, then repeat the process
 

### Adventure Mode

- [ ] Save the User's past results and display them if the user asks
- [ ] Allow the user to type in Morse Code and convert to English


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


## Additional Resources

- Bonus Video of me explaining Dictionaries and create a simple word count app.  https://www.youtube.com/watch?v=a2amPEI9AYM&index=28&t=0s&list=PLQohu2C4yKUugzokx9tOGVt9oamMMZBmR

