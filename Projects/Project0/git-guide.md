# Project 0 Git Guide

## Command Line Git

- status
  - Shows status of the local repository. This status includes:
    - number of local commits that have not been synced with remote (GitHub)
    - list of files in local folder than are NOT being tracked by git
    - list of files in local folder that have changes that need to be committed
  - `git status`
- clone
  - git clone allows you clone a copy of a repo from remote to local
  - In this class we use ssh to accomplish this 
  - `git clone git@github.com:*repositoryPath*`
- add
  - adds untracked files to be tracked
  - `git add *filePath*`
- rm
  - rm allows the user to remove files from tracking on github
  - `git rm *filePath*`
- commit
  - commit allows the user to record the changes the have made in their repository
  - a file has to be added for tracking before a commit can be made
  - it is best practice to use the -m flag to add a message to document the contents of the commit
  - `git commit -m "commit message" `
- push
  - push alows the user to update commited changes on local to remote
  - `git push`
- fetch
  - fetch allows the user to retreive an updated copy of the repository from remote
  - fetch does not merge the updates retreived from remote
  - `git fetch`
- merge
  - merge allows the user to update the local version of the repository with changes obtained by the fetch command
  - `git merge`
- pull
  - pull is a combination of the using fetch then merge
  - `git pull`
- branch
  - branch allows the user to have a separate version of the repository
  - the default branch for a repository is usually called main
  - main is used to be the working copy of the repository
  - other created branches allow the user to test changes without breaking the product
  - `git branch *branchName*`
- checkout
  - checkout allows you to switch which branch the user is working on
  - `git checkout *branchName*`
- ~~init~~
- ~~remote~~

## git files & folders

- .git folder
  - The .git folder contains all of the information for the repository to function on the local machine
  - This includes
    - hooks
    - objects
    - config
    - refs
    - HEAD
    - index
  - this folder is hidden by default
- .gitignore file
  - .gitignore file holds a list of files you want ignored
  - this is used so that files that you dont want tracked stop appearing in git status output
- ~~.git/hooks~~

## GitHub

- Pull requests
  - pull requests allow you to tell others about changes you have made
  - a forum is created where the changes can be discussed
- SSH authentication to repositories
  - this is the preferred way for connecting to github
  - password authentcation was depricated for not being a secure way to connect to github
  - to set this up the user needs to generate an ssh keypair on local and copy the public key to github
- ~~Actions~~