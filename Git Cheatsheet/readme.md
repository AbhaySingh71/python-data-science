# Git Cheat Sheet

## Setup & Configuration

- `git config --global user.name "Your Name"`  
  Set your global Git username.

- `git config --global user.email "your.email@example.com"`  
  Set your global Git email.

- `git config --list`  
  Show all configured Git settings.

---

## Repository Operations

- `git init`  
  Initialize a new Git repository.

- `git clone <repository-url>`  
  Clone a remote repository locally.

- `git remote add origin <repository-url>`  
  Add a remote repository URL.

- `git remote -v`  
  Show all configured remotes.

---

## Basic Commands

- `git status`  
  Check current repository status.

- `git add <file>`  
  Stage a specific file.

- `git add .`  
  Stage all changed files.

- `git commit -m "commit message"`  
  Commit staged changes with a message.

- `git push origin <branch>`  
  Push changes to the remote branch.

- `git pull origin <branch>`  
  Fetch and merge changes from remote.

---

## Branch Operations

- `git branch`  
  List local branches.

- `git branch -a`  
  List all branches (local + remote).

- `git branch <branch-name>`  
  Create a new branch.

- `git checkout <branch-name>`  
  Switch to an existing branch.

- `git checkout -b <branch-name>`  
  Create and switch to a new branch.

- `git merge <branch-name>`  
  Merge a branch into the current one.

- `git branch -d <branch-name>`  
  Delete a local branch.

- `git push origin --delete <branch-name>`  
  Delete a remote branch.

---

## History & Differences

- `git log`  
  Show full commit history.

- `git log --oneline`  
  Show compact commit history.

- `git diff`  
  Show unstaged changes.

- `git diff --staged`  
  Show staged changes.

- `git diff <commit1> <commit2>`  
  Compare two commits.

---

## Undo Operations

- `git reset <file>`  
  Unstage a file.

- `git reset --soft HEAD~1`  
  Undo last commit, keep changes.

- `git reset --hard HEAD~1`  
  Undo last commit and discard changes.

- `git revert <commit>`  
  Revert a specific commit with a new one.

---

## Stash Operations

- `git stash`  
  Temporarily save uncommitted changes.

- `git stash list`  
  List all stashed changes.

- `git stash apply`  
  Apply most recent stash (keeps stash).

- `git stash pop`  
  Apply and remove most recent stash.

- `git stash drop`  
  Delete most recent stash.

---

## Advanced Operations

- `git rebase <branch>`  
  Reapply commits on top of another branch.

- `git cherry-pick <commit>`  
  Apply a specific commit to the current branch.

- `git tag <tag-name>`  
  Create a lightweight tag.

- `git tag -a <tag-name> -m "message"`  
  Create an annotated tag with a message.

---

## Cleanup Operations

- `git clean -n`  
  Preview untracked files to be deleted.

- `git clean -f`  
  Delete untracked files.

- `git gc`  
  Clean up unnecessary files and optimize repo.

---

## Help

- `git help <command>`  
  Show help for a Git command.

- `git <command> --help`  
  Alternative way to get command help.

