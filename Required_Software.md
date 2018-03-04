# Required Dev tools 

Over the course the training you will be using a variety of tools. To get start we ned the follow software and tools


## Tools

### Node

#### What

Node is a runtime for javascript. This means that with node, we can run javascript on our machines without having to be in a browser

#### Why

For the first part of the training, we are concentrating on the HTML/CSS and JavaScript. Many useful tools for those languages are built with node. 

#### How

Run the installer here:
<br/>
[https://nodejs.org/en/](https://nodejs.org/en/)
 
```
```

- Yarn

#### What

Yarn is a package manager for node packages. This means that we can install and use libraries that are written in node.

#### Why

We will be using this to run our scripts and as well as installing needed packages. THis will be more useful as we continue deeper in JavaScript

#### How


Follow these instructions: 

[https://yarnpkg.com/lang/en/docs/install/](https://yarnpkg.com/lang/en/docs/install/)


### Surge

#### What 

Surge is a static website hosting company. It allows for easy deploy of your websites so they are on the web!

#### Why

We will use this to host some projects to see how the deploy process works

#### How

Once you have node installed, run the following command in powershell.

``` 
npm install --global surge

```

### git

#### What 

Git is a distributed source control system. This allows us work and collaborate on different projects with little to no headache.

#### Why

Git is how we will be managing our files and sharing code between each other. It will seem rough at first but with practice, you will never know how any else shares documents

#### How

Go here and download the install: 
[https://gitforwindows.org/](https://gitforwindows.org/)


NOTES: 
    - It will ask you about your path variable, I recommend selecting the third option `use git and optional unix tools`. This will allow git to be used in your terminal
    

### posh git

#### What 

`post-git` is a extenstion for powershell that allows easy management for git. It will give very useful information for us.

#### How

Follow these instructions
https://github.com/dahlbyk/posh-git#installation

to move on, you should be able to run `Import-Module posh-git` in a git repo and get a display.

### Set up to run everytime you open up powershell

- in powershell run, `code %UserProfile%\My Documents\WindowsPowerShell\profile.ps1`
- in the file that opens, add `Import-Module posh-git`. 
- save and close file
- restart powershell


### hub

#### What
 Hub is command line helper for github. It allows for easy github manipulation from powershell.

#### How
Download and run this installer: 
[https://github.com/github/hub/releases/download/v2.3.0-pre9/hub-windows-amd64-2.3.0-pre9.zip](https://github.com/github/hub/releases/download/v2.3.0-pre9/hub-windows-amd64-2.3.0-pre9.zip)

### VS CODE

#### What 
VS Code is a light weight text editor that produced by Microsoft that is being widely adopted by many developers. 

#### Why

Even though we will end our journey together with Visual Studio, We we be starting with something a bit less overwhelming. VS Code is a lightweight editor that allows us to see what is going on so when we get the more powerful tools (like Visual Studio). It will not be a crutch, but a tool. This is like starting with a screwdriver, and working our way up to power drill. 

#### How
Download here: 

(https://code.visualstudio.com/)[https://code.visualstudio.com/]
