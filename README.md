# Setting up Git
## Objectives and Outcomes
In this exercise you will learn to install Git on your computer. Git is required for using all the remaining Node.js and Node based tools that we encounter in the rest of the course. At the end of this exercise, you would be able to:

* Install Git on your computer

* Ensure that Git can be used from the command-line or command-prompt on your computer

* Set up some of the basic global configuration for Git

## Downloading and Installing Git :-
* To install Git on your computer, go to https://git-scm.com/downloads to download the Git installer for your specific computing platform.
* Then, follow the installation steps as you install Git using the installer.
* You can find more details about installing Git at https://git-scm.com/book/en/v2/Getting-Started-Installing-Git. This document lists several ways of installing Git on various platforms.
* Installing some of the GUI tools like GitHub Desktop will also install Git on your computer.
* On a Mac, setting up XCode command-line tools also will set up Git on your computer.
* You can choose any of the methods that is most convenient for you.

## Some Global Configuration for Git :-

* Open a cmd window or terminal on your computer.

* Check to make sure that Git is installed and available on the command line, by typing the following at the command prompt:
```
   git --version
```
* To configure your user name to be used by Git, type the following at the prompt:
```
   git config --global user.name "Your Name"
```
* To configure your email to be used by Git, type the following at the prompt:
```
   git config --global user.email <your email address>
 ``` 
* You can check your default Git global configuration, you can type the following at the prompt:
```  
   git config --list
```

# Setting Online Git Repositories
## Objectives and Outcomes
In this exercise you will learn about how to set up and use an online Git repository and synchronize your local Git repository with your online repository. At the end of this exercise, you will be able to:

* Set up the online repository as a remote repository for your local Git repository
* Push your commits to the online repository
* Clone an online Git repository to your computer
## Setting up an Online Git repository
* Sign up for an account either at Bitbucket (https://bitbucket.org) or GitHub (https://github.com). Note that private repositories on GitHub requires a paid account, and is not available for free accounts.
* Then set up an online Git repository named git-test. Note the URL of your online Git repository.
### Set the local Git repository to set its remote origin
* At the prompt, type the following to set up your local repository to link to your online Git repository:
```
   git remote add origin <repository URL>
```
### Pushing your commits to the online repository
* At the prompt, type the following to push the commits to the online repository:
```
   git push -u origin master
```   
### Cloning an online repository
* To clone an online repository to your computer, type the following at the prompt:
```
   git clone <repository URL>
```
