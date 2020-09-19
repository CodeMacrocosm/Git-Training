# git_intro


# Introduction to Version Control Using Git

## What is version control ?

Say you have a bunch of files that go together, such as source code for a project, or files for a website. Now if you want to keep an old version you have to archive a whole directory. Keeping many versions around by hand is inconvenient, and quickly becomes expensive.Version control systems are no different. They all have nice interfaces to manage a directory of stuff. You can save the state of the directory every so often, and you can load any one of the saved states later on.Version control systems are no different. They all have nice interfaces to manage a directory of stuff. You can save the state of the directory every so often, and you can load any one of the saved states later on.

### Learning Objectives:

* #### Learn basic command line interface commands
    * mkdir, cd, ls, rm, mv
    * installing git
* #### Learn basic git commands
    * log, status, diff, stash, commit, add, rm, .gitignore, branch, checkout
    * cloning, pulling, push
* #### Learn basic github actions:
    * pull requests, forking

## Setting up git !

Download & Install Git From: http://git-scm.com/downloads

In your command prompt or terminal use the following commands for respective operations.

### Configuring Git Settings (Initial Setup)

After installing git it is a good idea to introduce yourself to Git with your name and public email address before doing any operation. The easiest way to do so is:

`git config --global user.email "yourmail@example.com"`

`git config --global user.name "Your User Name Comes Here"`

### Checking Configuration

To check your credentials just run these commands git reply's with your name.

`git config user.name`

`git config user.email`

Make sure you run all these commands in your working folder / project folder

### Making Repos

`git init`

You've just told your computer that you want git to watch the 'myProject' folder and keep track of any changes; basically making it so you can now run git commands inside of this folder.

`git clone <url>`

The clone is on an equal with the original project, possessing its own copy of the original project’s history.It just downloads the source file.

### Adding Remote

`git remote add origin https://github.com/user/repo.git`

This remote helps you to interact with the same repository over and over again. By defining remote repository shorthand, you can make it easier.

### Checking Added Remote

`git remote -v`

### Making Changes

`git status`

Git briefs you about the current situation.  

`git add .`

Git to take a snapshot of the contents of all files under the current directory.

`git commit -m "Commit Message"`

If you need to make any further adjustments, do so now, and then add any newly modified content to the index. Finally, commit your changes with a commit message.

`git commit -am "Commit Message"`

This command makes you to run two commands, one adding all the files and commit changes.

### Pushing Repo Code

`git push origin master `

This is used to push commits made on your local branch to a remote repository.

### Fetching and Pull

`git fetch`

`git pull `
