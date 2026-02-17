# Git Commands Notes
## Check Current Branch
git branch


Lists all local branches.

* shows the branch you are currently on.

## Pull Latest Changes from Remote main
git pull origin main


Updates your current branch with the latest changes from main on GitHub.

Keeps your branch up-to-date before making new changes.

## Stage Changes
git add .


Adds all new and modified files in the current directory to the staging area.

Prepares them for commit.

## Commit Changes
git commit -m 'added scope examples and notes'


Saves your staged changes locally with a message describing what you changed.

Commit messages should be short and clear.

## Push Changes to Remote Branch
git push origin fundamentals


Sends your local commits to the fundamentals branch on GitHub.

Updates the remote repository so others can see your changes