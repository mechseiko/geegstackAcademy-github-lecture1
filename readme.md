#  Git Intro

This is a project on git lectures
This is a Markdown file 
It is where some information about the project is written


We can decide to commit the changes that we've made to git
this is made acheivable using the git commit command
A message can also be added to the commit using the m flag {-m}


Committing a project to Git is like saving a snapshot of your work. Here’s how you do it:

-----Steps to Commit a Project to Git-----
1. Initialize Git (if not already initialized)
git init
This creates a .git folder, making your project a Git repository.

2. Check the status of your files
git status
This shows which files have been modified or are untracked.

3. Stage the files you want to commit
git add .
This stages all changes. You can also add specific files:
git add filename.ext


4. Commit the changes with a message
git commit -m "Your commit message here"
The message should describe what changes you made.

5. Connect to a remote repository (if needed)
git remote add origin <repository-URL>


Example for GitHub:
git remote add origin https://github.com/yourusername/repository.git
Push the commit to the remote repository

git push -u origin main
If your branch is named master, use master instead of main.