# Robots, Humans, Pandas and SOLID

Tonight you will be making a few classes that inherit from a base class and also reading about some OOP design princples 


## Objectives

- Practice and understand Inheritance
- Read about SOLID

### Explorer Mode

- [ ] Start by Creating 3 classes, Human, Panda & Robot
- [ ] All three classes have a Name and Birthday
- [ ] Robots have a `VersionNumber` 
- [ ] All three classes have a boolean property, `IsAsleep` that is private 
- [ ] The Human and Panda classes have a Method call `WakeUp()` and `FallAsleep()` that toggles the `IsAsleep` property
- [ ] The Robot has a `StartUp()` and `ShutDown()` that toggles the `IsAsleep` property
- [ ] The Human and Panda have a `Eat(string food)` Method that prints out that object is eating
- [ ] All three classes have a `SayHello()` Method that say that classes greeting
- [ ] Human can have many pets. Both a Panda and Robot can be pets
- [ ] Humans have a `Adopt(Pet pet)` method that adds a Pet to their own Pet list
- [ ] All Pets have `OwnersName` property that is only set when a pet is Adopted by a Human
- [ ] Override all the `ToString()` to print out all the properties

- [ ] Create a small sample app that demonstrates:
  - [ ] All the Methods above
  - [ ] Putting a type of each class into an List
  - [ ] each Class waking up/falling asleep, eating( if not a robot) , and saying hello
  - [ ] A Human should adopt both a Robot and Panda

 
- [ ] Read these articles, we will be discussing them together in lecture
  - https://scotch.io/bar-talk/s-o-l-i-d-the-first-five-principles-of-object-oriented-design 
  - http://deviq.com/solid/

### Adventure Mode
- [ ] Go back to a C# assignment and refactor to use classes
- [ ] Make Classes for a `Bike`, `Unicycle`, `Car`, `Truck`, and `MotorCycle` using interfaces and parent classes to reduce code duplication 

### Epic Mode
- [ ] Allow users to create and name a new Humans
- [ ] Allow the user, as a human, to adopt as many Robots and Pandas as possible
- [ ] Save your classes and data to a file, and load them when the starts


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


## Additional Resources
- A small video on inheritance and interfaces: 
Inheritance: https://www.youtube.com/watch?v=m0DJIhmUtP8&t=0s&list=PLQohu2C4yKUugzokx9tOGVt9oamMMZBmR&index=21
Interfaces: https://www.youtube.com/watch?v=neTerkT7LhE&t=0s&list=PLQohu2C4yKUugzokx9tOGVt9oamMMZBmR&index=20