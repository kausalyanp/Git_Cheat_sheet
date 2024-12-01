# Git Cheat Sheet
It contains all commonly and uncommonly used git commands with explanation.

## 1. Setup and Configuration:
1. Sets the username for all repositories on your machine.
```
git config --global user.name "Your Name"
```
2. Sets the email for all repositories on your machine.
```
git config --global user.email "you@example.com"
```
3. Displays all configuration settings.
```
git config --list
```
4. Sets the default text editor for Git (e.g., vim, nano).
```
git config --global core.editor <editor>
```
5. Creates a shortcut for a Git command.
```
git config --global alias.<alias-name> <command>
```
## 2. Creating and Initializing Repositories
1. Initializes a new Git repository in the current directory.
```
git init	
```
2. Creates a local copy of a remote repository.
```
git clone <repository-url>
```
## 3. Staging and Committing Changes
1. Adds a file to the staging area.
```
git add <file>
```
2. Adds all changes in the current directory to the staging area.
```
git add .
```
3. Creates a commit with the specified message.
```
git commit -m "Commit message"
```
4. Stages and commits all tracked files in one step.
```
git commit -a -m "Commit message"
```
5. Unstages a file from the staging area.
```
git restore --staged <file>
```
## 4. Viewing Changes and Logs
1.  Displays the status of files in the working directory and staging area.
```
git status
```
2. Shows differences between the working directory and the staging area.
```
git diff
```
3. Shows differences between the staging area and the last commit.
```
git diff --staged
```
4. Displays a history of commits.
```
git log
```
5. Shows a condensed commit history.
```
git log --oneline
```
6. Displays details of a specific commit.
```
git show <commit-hash>
```
## 5. Branching and Merging
1. 











