## Git Branching Cheat Sheet

### Basic git Commands
* `git init` - initialize working directory with git repository
* `git status` - show status of working directory/repository
* `git add` - stage changes for commit
* `git commit -m "Message"` - commit staged changes to local repository
* `git log` - list commits
* `git log --oneline`- list commits in compact format
* `git config --list` - list current git configuration
* `git config --help` - shows list of commands

### Remote Commands
* `git pull origin main` - pull remote branch `main` into current local branch
* `git push origin main` - push local commits to remote repository

### Branching Commands
* `git branch -M newName` - Rename current branch to `newName`
* `git branch newBranch` - Create Branch `newBranch`
* `git branch` - lists local branches, indicating current branch
* `git checkout newBranch` - Make `newBranch` the current branch
* `git checkout -b otherBranch` - Create and checkout `otherBranch`
