##  Git and Git Branching Cheat Sheet

categories of git  commands, and practice with branching


### Basic commands
* `git init` - initialize current directory with repository
* `git add .` - add all files in current directory to git index, staging them for  commit
* `git commit -m"some message"` -commit  staged  changes to local repository

### Info commands

* `git status`- show status of current working directory
* `git log` - list commit history
* `git log --oneline` - list commit history(compact)
* `git config -l` - list local git configuration settings

### Branch commands
* `git branch` - list local branches, , highlight current branch
* `git branch  branchName` - create  branch `branchName`
* `git checkout branchName` - switch to branch `branchName`
* `git checkout -b otherBranch`  - switch to branch `otherBranch`, creating it if it doesn't exist

### Remote commands
* `git remote add origin someUrl` - connect  local repository to remote repository url as  `origin`
* `git  push origin branchName` - push local commits to remote repository into branch `branchName`
* `git pull origin branchName` - pull  remote branch `branchName` into local current branch

### Other commands
* `git help` - list git subcommands and options
* `git config --help` - show options for  `git config`
