#  Git Training: "Unlock Git Mastery: Elevate Your Collaboration Game! 🚀💻🌐 📘🚀

🌟🌟🌟🌟

[![GitHub stars](https://img.shields.io/github/stars/CodeMacrocosm/Git-Training?style=flat-square)](https://github.com/CodeMacrocosm/Git-Training/stargazers)

[![GitHub forks](https://img.shields.io/github/forks/CodeMacrocosm/Git-Training?style=flat-square)](https://github.com/CodeMacrocosm/Git-Training/network)

🌟🌟🌟🌟

## Table of Contents

1. [Overview](#overview)
2. [Introduction to Version Control Using Git](#introduction-to-version-control-using-git)
3. [Setting up Git](#setting-up-git)
4. [Git Cheat Sheet](#git-cheat-sheet)
5. [Uploading Files to GitHub with Branching](#uploading-files-to-github-with-branching-)
6. [Why This Git Training?](#-why-this-git-training)
7. [License](#-license)
8. [Star This Repository](#-star-this-repository)
9. [Conclusion](#conclusion)

---

## Overview

Welcome to Git Training, a Hands-On Training repository led by **Shreya Malogi**! 🌟 comprehensive guide to getting started with Git. This training edition covers not only the basic GitHub workflow but also provides an introduction to version control using Git, essential command-line interface commands, and a Git cheat sheet. 📘🚀

## Introduction to Version Control Using Git

### What is Version Control?

Version control allows you to manage a 🔄 collection of files, such as 💻 source code for a project or 📁 files for a website, by 🕰️ keeping track of changes over time. It eliminates the ✨ need to archive entire directories to 🤝 maintain different versions manually. Git, a distributed version 🌐 control system, is widely used for efficient collaboration and code management.


### Learning Objectives

1. Learn basic command-line interface commands:
   - `mkdir`, `cd`, `ls`, `rm`, `mv` 💻
2. Installing Git
3. Learn basic Git commands:
   - `log`, `status`, `diff`, `stash`, `commit`, `add`, `rm`, `.gitignore`, `branch`, `checkout` 🚀
   - Cloning, pulling, push 🔄
4. Learn basic GitHub actions:
   - Pull requests, forking 🌐

### Setting up Git

Download & Install Git from [git-scm.com](http://git-scm.com/downloads). ⬇️

#### Configuring Git Settings (Initial Setup) 🤖

After installing Git, introduce yourself to Git with your name and public email address:

```bash
git config --global user.email "yourmail@example.com"
git config --global user.name "Your User Name Comes Here" 
```

#### Checking Configuration 🕵️

To check your credentials:

```bash
git config user.name 
git config user.email 
```

*Make sure you run these commands in your working folder/project folder.* 📂

### Git Cheat Sheet 

| Command | Description |
| ------- | ----------- |
| `git init` | Initialize a new Git repository 🔄
| `git clone <url>` | Clone a repository into a new directory 📂
| `git remote add origin <url>` | Add a remote repository 🌐
| `git remote -v` | Display remote repositories 📊
| `git status` | Show the working tree status 🌳
| `git add .` | Add changes to the index ➕
| `git commit -m "Commit Message"` | Commit changes with a message 📝
| `git commit -am "Commit Message"` | Add and commit changes in one command 📦
| `git push origin master` | Push commits to a remote repository 🚀
| `git fetch` | Download objects and refs from a remote repository 📥
| `git pull` | Fetch from and integrate with another repository or a local branch 🔄
| `git branch` | List, create, or delete branches 🌿
| `git checkout <branch>` | Switch branches or restore working tree files 🔄
| `git merge <branch>` | Join two or more development histories together 🤝
| `git log` | Show the commit logs 📜
| `git diff` | Show changes between commits, commit and working tree, etc. ↔️
| `git stash` | Stash changes in a dirty working directory away 📥
| `git rm <file>` | Remove files from the working tree and from the index ❌


 ## Uploading Files to GitHub with Branching" 🚀📂

 Here's the complete set of commands to upload files to GitHub using Git, including creating a new branch:

1. **Initialize a Git Repository:**
   ```bash
   git init
   ```

2. **Add Files to the Staging Area:**
   ```bash
   git add .   # Add all files
   ```

   or

   ```bash
   git add <file1> <file2>   # Add specific files
   ```

3. **Commit Changes:**
   ```bash
   git commit -m "Your commit message here"
   ```

4. **Create a New Branch:**
   ```bash
   git branch <branch-name>
   ```

   This command creates a new branch but doesn't switch to it.

5. **Switch to the New Branch:**
   ```bash
   git checkout <branch-name>
   ```

   or, using the more recent `git switch` command:

   ```bash
   git switch <branch-name>
   ```

   Alternatively, you can combine branch creation and switching in one command:
   ```bash
   git checkout -b <branch-name>
   ```

6. **Make Changes, Add, and Commit in the New Branch:**
   ```bash
   git add .
   git commit -m "Your commit message here"
   ```

7. **Add a Remote Repository (GitHub):**
   ```bash
   git remote add origin https://github.com/your-username/your-repository.git
   ```

8. **Push the Changes to GitHub:**
   ```bash
   git push -u origin <branch-name>
   ```

   The `-u` option sets the upstream branch for the new branch.

Now, you've initialized a Git repository, added files, committed changes, created a new branch, made changes in the new branch, and pushed the changes to GitHub. Remember to replace `your-username`, `your-repository`, and `<branch-name>` with your actual GitHub username, repository name, and the desired branch name.

Happy coding and branching! 🚀🌿



## 🎯 Why This Git Training?

Whether you're a Git novice or eager to enhance your skills, this hands-on experience,  ensures effective learning.


## 📜 License

Open-source under the MIT License.

MIT License

Copyright (c) 2020 CodeMacrocosm

## 🌟 Star This Repository

Show support if you find it helpful!

## Conclusion

Congratulations! You've completed this extended tutorial and have a solid foundation in using  Git for version control. Use the provided Git cheat sheet as a quick reference, and explore more about the power of pull requests in the [GitHub Flow Guide](https://guides.github.com/introduction/flow/). 🌟

Happy coding! 🚀🎉✨👩‍💻🌟🏁


## 🚀 Let's Get Started!

Begin your Git journey today. Happy Learning! 🌟"
