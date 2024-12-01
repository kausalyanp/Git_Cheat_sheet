# Git Cheat Sheet
It contains all commonly and uncommonly used git commands with explanation.

Table of Contents:
1. [Setup and Configuration](#1-setup-and-configuration)
2. [Creating and Initializing Repositories](#creating-and-initializing-repositories)
3. [Staging and Committing Changes]()
4. [Viewing Changes and Logs]()
5. [Branching and Merging]()
6. [Remote Repositories]()
7. [Tagging]()
8. [Undoing Changes]()
9. [Stashing Changes]()
10. [Advanced Operations]()
11. [Collaboration and Contributing]()

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
1. Lists all branches in the repository.
```
git branch
```
2. Creates a new branch.
```
git branch <branch-name>
```
3. Switches to the specified branch.
```
git checkout <branch-name>
```
4. Another way to switch branches.
```
git switch <branch-name>
```
5. Creates and switches to a new branch.
```
git checkout -b <branch-name>
```
6. Merges the specified branch into the current branch.
```
git merge <branch-name>
```
7. Deletes the specified branch.
```
git branch -d <branch-name>
```
## 6. Remote Repositories
1. Links a local repository to a remote repository.
```
git remote add origin <url>	
```
2. Lists remote connections.
```
git remote -v
```
3. Pushes commits from the local branch to the remote branch.
```
git push origin <branch-name>
```
4. Fetches changes from the remote repository without merging them.
```
git fetch
```
5. Fetches and merges changes from the remote repository.
```
git pull
```
6. Pushes a new branch and sets it to track the remote branch.
```
git push --set-upstream origin <branch-name>
```
## 7. Tagging
1. Creates a lightweight tag for the current commit.
```
git tag <tag-name>
```
2. Creates an annotated tag.
```
git tag -a <tag-name> -m "Message"
```
3. Displays details about a tag.
```
git show <tag-name>
```
4. Pushes a tag to the remote repository.
```
git push origin <tag-name>
```
5. Pushes all tags to the remote repository.
```
git push --tags
```
## 8. Undoing Changes
1. Restores a file to its last committed state.
```
git restore <file>	
```
2. Resets the current branch to the specified commit.
```
git reset <commit>
```
3. Resets to the commit but keeps changes staged.
```
git reset --soft <commit>
```
4. Resets to the commit and removes all changes.
```
git reset --hard <commit>
```
5. Creates a new commit that undoes the changes from a specific commit.
```
git revert <commit>
```
## 9. Stashing Changes
1. Temporarily saves changes without committing them.
```
git stash
```
2. Lists all stashes.
```
git stash list
```
3. Applies a specific stash.
```
git stash apply <stash>
```
4. Applies and removes the most recent stash.
```
git stash pop
```
5. Deletes a specific stash.
```
git stash drop <stash>
```
## 10. Advanced Operations
1. Applies a specific commit to the current branch.
```
git cherry-pick <commit>
```
2. Moves the base of the current branch to the specified branch.
```
git rebase <branch-name>
```
3. Displays a log of all reference updates (useful for recovery).
```
git reflog
```
4. Helps identify the commit that introduced a bug.
```
git bisect
```
## 11. Collaboration and Contributing
1. Creates a personal copy of a repository on GitHub or similar platforms.
```
git fork
```
2. Fetches changes from the original repository of a fork.
```
git fetch upstream
```
3. Replays local commits on top of the upstream branch.
```
git rebase upstream/<branch>
```

###
Created By Kausalya N P
>> Users can copy this repo for educational purpose.
###

















