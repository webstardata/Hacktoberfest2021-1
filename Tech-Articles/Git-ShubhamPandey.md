
=======================================================

Article Title: Git

Author Name: Shubham Pandey

Author Profile: https://github.com/shubh4122

Date: 17-10-2021

=======================================================

## What is Git?
Git is a Distributed Version Control System, in short.
"Version Control System" as the name suggests, is something that helps in controlling the different 
versions of the application one is making.

## Why we need Git?
Suppose you were working on a project(say an app) and you somehow messed with the codebase which now gives undesired results.
The only thing you would want is to go back to the previous version of that app. But how?

Here comes GIT into the picture!

In layman's language it simply helps you by taking sort of 'snapshots' of your codebase whenever asked to and
stores them in a place called "Git Repository".
Now you can add any other feature to the app or make change to its codebase without any worry of messing up with your project.
That sounds cool, right?

## How to use?
Git can be used either by a CLI(Git Bash preferably) or by a GUI offered by Git itself.
Though, I prefer CLI over GUI.

Below are the steps to use git using GIT BASH(CLI).

## Basic Commands and Instructions to use Git:
### Steps:
Zeroth step is to Create/Browse to the desired folder which you wish to make a git repository.
All the project related files remain in this folder.

    Using cd <dir_name> to change dir or mkdir <dir_name> to create dir

Firstly, we create/initialize a Git repo.

    git init
    
Then, we can make any amount of changes in the working dir, regarding our project.
Now we wish to save those changes.
We First need to stage those changes. Its like in a party, guests are first called on the stage and then their photo is clicked.
Git works similarly. It first stages the files, then commits them. By commit I mean, taking "snapshot" and saving them in repo.

So to add files, use:

    git add <file_name>
    
Now we can commit those changes using:

    git commit -m "Commit Message"
    
We can also check the status of the repo by:

    git status
    
We can also check all the commit related info by:

    git log
    

## Outro
This is just a short article about Git. There are many things regarding git and its commands that arent covered in this article.
So to learn more about Git I am attaching some of the resources below:

- [Git Official Website](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control)
- [Version Control with Git](https://classroom.udacity.com/courses/ud123)
- [Git/Github tutorial by Kunal Kushwaha](https://youtu.be/apGV9Kg7ics)

### Suggestions, to improve this article are most Welcome!! :-)
