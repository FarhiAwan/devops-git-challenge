# Proof of Work

## Git Log

504235c Add deploy.sh and README.md



&#x20;Questions



Q1: Difference between Git and GitHub

Git is a version control tool that runs on my own computer and tracks changes to files locally. It lets me create commits, branches and merges without needing the internet. GitHub is a cloud platform that hosts Git repositories online. It adds collaboration features such as Pull Requests, issues and access control. I can use Git without GitHub, but GitHub depends on Git.



Q2: Working Directory, Staging Area and Local Repository

The working directory is the folder where I create and edit files. The staging area is where I place selected changes using git add, to prepare them for the next commit. The local repository, stored in the .git folder, keeps the permanent history of commits. Changes move from the working directory to the staging area and then to the local repository.



Q3: git stash pop vs git stash apply

Both commands bring back changes that were saved with git stash. git stash pop restores the changes and then deletes that entry from the stash list. git stash apply restores the changes but keeps the entry in the stash list. Apply is useful when I want to reuse the same stash on another branch.



Q4: git fetch vs git pull

git fetch downloads new commits from the remote repository but does not change my working files or current branch. This lets me review the changes first. git pull does a fetch and then merges the changes into my current branch. So pull updates my files immediately, while fetch is the safer option.

