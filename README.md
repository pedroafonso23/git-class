# GIT and GITHUB - Pratical Guide

# Installation: https://git-scm.com/download

# Scenes

- You wish to create points in the production history of your project
- You wish to verify changes made in your project

- You begin a new feature in your project without messing with what already was done
- You add the new features in your project in production
- You want to delete the branch of the new feature, after you applied it to your project

- You wish to upload your project to the cloud

# My notes

Initialize timeline: git init

Add file to git: git add landingpage.html
To add everything in the root: git add .

Commit: git commit -m "added landing page"

--- file was modified ---

See log: git log

See status: git status

See commit details: git show <commit code>

Create a branch: git branch <branch name>
See all the branches: git branch

Change to branch: git checkout <branch name>
Change to master: git checkout master

To merge a branch to the master: git merge <branch name>

Delete branch after merge: git branch -D <branch name>

--- GITHUB ---

You always have to create a repositoy on GitHub

Then execute: git remote add origin https://github.com/pedroafonso23/<repository name>.git 

To see remote repositories: git remote -v

For the first push (create master): git push -u origin master



