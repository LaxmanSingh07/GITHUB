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

git push origin <new-branch-name> # it will create the branch on the github (online)


# create and switch to the branch
git checkout -b <branch-name> # b is here for branch

# 👉 Merge branch

# first of all we have to switch to the branch where we want to merge the branch
# then

git merge <branch-name>

# to delete the branch

git branch -d <branch-name>

# you can also delete the branch from the github (online)

git push origin --delete <branch-name>


# if i want to delete the branch from the github (online) and locally

# if i have creted a branch and now I have changed something in the branch from which i have crated the branch and now i want those changes in the new branch then i can use the following command

git pull origin <branch-name> # it will pull the changes from the branch from which i have created the branch

```

##### You can add and commit a file at once by using the following command

```bash

git commit -am "commit message"

# but it only works for the tracked files

# you need to do atleast one add and commit for the untracked files



git branch -v # it will show the last commit message of the branch (all branches remote + local) v for verbose detail

git branch -r # it will show the remote branches


git branch --merged # it will show the merged branches


git branch --no-merged # it will show the unmerged branches

# delete the merge which is not merged


# if i will try to delete the branch which is not merged then it will give me the warning the reason is that if i will delete the branch then i will lose the data


git branch -D <branch-name> # it will delete the branch forcefully

# -u is for upstream i.e. i can also pull the data from the branch

```
