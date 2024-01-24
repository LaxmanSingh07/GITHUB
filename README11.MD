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

## GIT RESET

- There are three types of reset

  - Soft reset
  - Mixed reset
  - Hard reset

- Soft reset

we can write the command in the following way

```bash

git reset --soft commit_id # you can find the commit id from the git log

# if you just want to remove the last commit then you can write

git reset --soft HEAD~1 # changes will also be in the staging area

```

- Mixed reset

we can write the command in the following way

```bash

git reset --mixed commit_id # you can find the commit id from the git log

# if you just want to remove the last commit then you can write

git reset --mixed HEAD~1 # changes will also be in the working directory

# the default reset is mixed reset

# we can just write

git reset # it will also do the mixed reset for the last commit



```
