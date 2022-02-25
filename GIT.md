# Git cheatsheet

## git status
Shows the current status of all files, can be used to identify files with un-staged, or un-committed changes

## git add <FILES>
Stages changes ready for committing 

NB: replace <FILES> with the files you want to add, `.` would mean all files in the current directory 

## git commit
Commits the staged changes

NB: Specifiy a message with -m "Message"

## git push
Pushes all commits to the remote repository

## git pull
Pulls all changes from the remote repository into our local

## git init
Initialises a repository in the current directory

## git clone
Clones a remote repository to the local machine

## git branch
Shows a list of all branches in the repository

NB: with the `-a` flag this will show remote branches as well as local 

## git checkout
Used for changing branches

See Also: git switch

## git checkout -b 
Creates a new local branch and checks it out

## git checkout -t
Checks out a local version of a remote branch 

## git log
Shows a history of commits in the repository