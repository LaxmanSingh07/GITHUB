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
# squash commit_id commit message 2
# squash commit_id commit message 3

# pick means keep the commit as it is
# squash means merge the commit with the previous commit

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

# we can also use the HEAD~0 , HEAD~1 ... to revert the last commit

git revert HEAD~1

# it will open the editor where we can write the message and then save and exit

# then the changes will be reverted

```

## GIT RESET

It is little confusing because it is used to reset the changes.

- There are three types of reset

  - Soft reset
  - Mixed reset
  - Hard reset

- Soft reset

  By the help of soft reset commit will be gone but the changes will be in the staging area.

we can write the command in the following way

```bash

git reset --soft commit_id # you can find the commit id from the git log

# if you just want to remove the last commit then you can write

git reset --soft HEAD~1 # changes will also be in the staging area

```

- Mixed reset

With the help of mixed reset commit will be gone but the changes will be in the working directory.

we can write the command in the following way

```bash

git reset --mixed commit_id # you can find the commit id from the git log

# if you just want to remove the last commit then you can write

git reset --mixed HEAD~1 # changes will also be in the working directory

# the default reset is mixed reset

# we can just write

git reset # it will also do the mixed reset for the last commit



```

- Hard reset

With the help of hard reset commit will be gone and the changes will also be gone.

we can write the command in the following way

```bash

git reset --hard commit_id # you can find the commit id from the git log

# HEAD~  it is for the current commit
```

<!-- -->
