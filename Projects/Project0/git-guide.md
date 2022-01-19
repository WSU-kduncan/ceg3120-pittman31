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
  - `git clone git@github.com:"repositoryPath"`
- add
  - adds untracked files to be tracked
  - `git add "filePath"`
- rm
  - rm allows the user to remove files from tracking on github
  - `git rm "filePath"`
- commit
  - commit allows the user to record the changes the have made in their repository
  - a file has to be added for tracking before a commit can be made
  - it is best practice to use the -m flag to add a message to document the contents of the commit
  - `git commit -m "commit message" `
- push
- fetch
- merge
- pull
- branch
- checkout
- ~~init~~
- ~~remote~~

## git files & folders

- .git folder
- .gitignore file
- ~~.git/hooks~~

## GitHub

- Pull requests
- SSH authentication to repositories
- ~~Actions~~