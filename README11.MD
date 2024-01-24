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

# then checkout to the main branch
# i means interactive

git checkout main

# then merge the branch1 to the main branch

git merge branch1

```
