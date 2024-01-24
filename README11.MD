## Git Squash

- Git squash is a way to condense multiple commits into one commit before merging them into a branch.

- It is a way to condense multiple commits into one commit before merging them into a branch.

we can write the command in the following way

```bash

# first checkout to the branch1

git checkout branch1

# then squash the branch1 to the main branch

git rebase -i main

git rebase -i HEAD~3 # it will squash the last 3 commits

# then i will get a file where i have to write the following command

# pick 1f3a6c3 commit message 1
# squash 1f3a6c3 commit message 2
# squash 1f3a6c3 commit message 3

# then save and exit

# then checkout to the main branch
# i means interactive

git checkout main

# then merge the branch1 to the main branch

git merge branch1

```

## GIT REVERT

- It is used to undo the changes of a commit.

we can write the command in the following way

```bash

git revert commit_id # you can find the commit id from the git log



```
