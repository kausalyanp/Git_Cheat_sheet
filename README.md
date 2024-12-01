# Git Cheat Sheet
It contains all commonly and uncommonly used git commands with explanation.

## Setup and Configuration:
1. Creates a personal copy of a repository on GitHub or similar platforms.
```
git config --global user.name "Your Name"
```
2. Fetches changes from the original repository of a fork.
```
git fetch upstream
```
3. Replays local commits on top of the upstream branch.
```
git rebase upstream/<branch>
```
