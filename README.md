**Stash**

git stash - Stash your changes

git stash push -m "message" - Stash with a message

git stash list - List all stashes

git stash branch <branchname> - Create a branch from a stash

git stash apply - This command restores your most recent stashed changes

git stash apply stash@{n} - Restore a specific stash from the list

git stash drop stash@{n} - Delete a specific stash when you no longer need it

git stash clear - Delete all your stashes at once



**Branch**

Rename a branch: git branch -m old-name new-name

List all branches: git branch

Switch branches: git checkout branch-name or git switch branch-name

Delete a branch (not merged): git branch -D branch-name

See which branch you're on: git status


**Merge**

git merge - Merge a branch into your current branch

git merge --no-ff - Always create a merge commit

git merge --squash - Combine changes into a single commit

git merge --abort - Abort a merge in progress


**Undoing and Amending Changes**

git restore <file> - Undo changes in your working directory (before staging).

git restore --staged <file> - Unstage a file (move it out of the Staging Area).

git reset HEAD~ - Undo your last commit (keeps changes in your working directory).

git commit --amend - Change the last commit message or add files to your last commit.

**Summary**

[Git Summary](https://www.w3schools.com/git/git_glossary.asp?remote=github)
