### Branching in the Github

- Branching is the way to work on different versions of a repository at one time.

- By default your repository has one branch named main which is considered to be the definitive branch. We use branches to experiment and make edits before committing them to main.

- I don't want to do the multiple commit on the main branch i want only when the all the features of the project is ready.

```bash

# 👉 Check all branches

git branch

# 👉 Create new branch

git branch <branch-name>

# 👉 Switch to another branch

git checkout <branch-name>

# 👉 Create new branch and switch to that branch

git checkout -b <branch-name> # b is here for branch

# 👉 Merge branch

# first of all we have to switch to the main branch
# then

git merge <branch-name>

# to delete the branch

git branch -d <branch-name>

# if you want to delete the branch forcefully

git branch -D <branch-name>

# you can also delete the branch from the github (online)

git push origin --delete <branch-name>

```