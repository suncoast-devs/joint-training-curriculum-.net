# Octodex

GitHub has a great mascot called OctoCat. OctoCat even has it's own gallery of variations, created by GitHub itself and fans, called [Octodex](https://octodex.github.com).

Unfortunately, the Octodex is not responsive*! Today, your task is to recreate the layout of The Octodex as closely as possible, but make it responsive. You can use all the tools you have at your disposal to get the job done. Use your browser's Developer Tools to inspect their site to find the exact font sizes and padding amounts.

![Octodex](https://tiy-learn-content.s3.amazonaws.com/ec8b2d13-octodex.png)

\* Well, _actually_ it uses javascript set the number of columns on page load, but we want to see interactive responsiveness when we resize our window!

## Objectives

- Build on your knowledge of HTML & CSS
- Implement a responsive design with media queries
- Implement, from scratch, a given design
- Understand HTML/CSS Layout
- Be able to place elements on a page where you want them.
- Use flexbox techniques layout pages.

## Requirements

- You should strive to implement the design as close as possible, though, especially if you've never touch HTML or CSS before, this can be extraordinarily difficult, and will take a lot of practice and mileage.

- **Note**: You should complete at least the tasks given for _explorer_ mode as listed below before turning in the assignment, as well as before attempting _adventure_ or _epic_ modes.

### Explorer Mode

- [ ] Recreate the page as closely as you possibly can. Use the same fonts, sizes, and colors. Download some of your favorite - [ ] Octocat images to use in your page (12-16 or so). Your layout should be flexible, but doesn't need to _perfectly_ responsive. 
- [ ] Use flexbox styles to layout the header and the Octocats (hint: checkout the `flex-wrap` property).

## Adventure Mode

- [ ] If you're feeling adventurous, use CSS _media queries_ to resize the Octocat containers to look great as a single full-width column on small screens, and a nice grid on bigger screens.

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
