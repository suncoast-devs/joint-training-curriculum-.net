# Title

basic grade book....?


enter a students name, a score, add it to a table


## Objectives

### Setup

- First, ensure you have the [`app-app` generator](https://github.com/tiy-tpa-fee/app-app) installed. We may have done this in class, *you only need to install `app-app` once* :

  ```sh
  npm install -g app-app
  ```

  Also, set up hub to use `HTTPS` rather than `SSH` for repositories:

  ```sh
  git config --global hub.protocol https
  ```

- Open your Terminal and create and change into the project's directory:

  ```sh
  mkdir -p ~/training/week-1/day-1/hello-world
  cd ~/training/week-1/day-1/hello-world
  ```

- Run the generator to create a boilerplate project:

  ```sh
  app-app --alpha --vscode
  ```

  Answer "Yes" to the questions about GitHub and Yarn.

- Open the project folder in VS Code:

  ```sh
  code .
  ```

  Remember `.` is an alias for the current directory.

- Using the file browser in your editor, open the file `public/index.html` and format your essay with HTML tags and place them into the document (remember all content goes _inside_ the `<body>` tags). Don't worry about the other files in the directory for now, we'll talk about those later, right now, we're mostly concerned with the two files in `public`; `index.html` and `screen.css`.

### Explorer Mode

- [ ] this is a requirement


### Adventure Mode

- [ ] this is a requirement


### Epic Mode

- [ ] this is a requirement

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
