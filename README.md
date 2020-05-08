# Python4Data_science Introduction
This is my JupyterLab files where you can follow my machine learning pathway. I have used Python for a year before I begin this course on Python for Data Science by IBM.

# Some basic Git command
---
In your Git project directory, use

- `ls -la' to show the listing of all the files including the /.git one. If you don t see a /.git file, then `git' is not tracking the project. Hence, we initialise the reprository with
- git init
Now if you type `git status', you will see .git folder
- git status # give you the list of all untracable file
- git add . 
- git commit -m "Initial Commit" # to add all the project files
- git log # We should see that the head is pointing to a serie of number. We are therefore ready to start tracking our changes.
- git status 

Before pushing from your local directory to the remote repository, make sure that you pull all the files from the remote to the local one. Also, use `git push --force origin master' with precaution. It will delete the files in your remote repository that are not pull into your local/working folder.
---
- git pull --rebase origin
- git push origin master


