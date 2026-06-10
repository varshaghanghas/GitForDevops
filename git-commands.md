# Git Commands Reference

## Setup & Config
- `git config`: Configures Git settings like user identity.
  _Example:_ `git config --global user.name "Varsha Ghanghas"`
- `git init`: Creates a new local Git repository.
  _Example:_ `git init`

## Basic Workflow
- `git status`: Shows the state of the working directory and staging area.
  _Example:_ `git status`
- `git add`: Adds file changes to the staging area.
  _Example:_ `git add git-commands.md`
- `git commit`: Saves staged snapshots to the permanent history.
  _Example:_ `git commit -m "feat: initial commit"`

## Viewing Changes
- `git diff`: Shows differences between files in the working directory and the staging area.
  _Example:_ `git diff git-commands.md`
- `git log`: Displays the history of commits.
  _Example:_ `git log --oneline`

## Git Branching
- `git checkout -b devops`: create new branch called `devops` and moved to `devops` branch.
- `git branch`: Lists, creates, or deletes branches.


## Remote repositories
- `git push`: Push changes from local to remote directory on github. Only push changes to the current branch you are working in.
- `git push origin main`: Can reference the branch to push changes.