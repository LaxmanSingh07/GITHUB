### GIT REBASE

`It is some how similar to merge but it is not merge.`
`Suppose i am rebasing the branch1 to the main branch` then it will take all the commits from the branch1 and put it on the top of the main branch. It will not create any new commit. But branch2 will also hold the commits history as the main branch.`after the rebase` the new commit id is also different from the old commit id.

`we can write the command in the following way`

```bash

# first checkout to the branch1

git checkout branch1

# then rebase the branch1 to the main branch

git rebase main

# then checkout to the main branch

git checkout main

# then merge the branch1 to the main branch

git rebase branch1


# if you have any rebase conflict then you have to resolve it manually

# after resolving the conflict you have to add the file to the staging area you have to write

git rebase --continue # it will continue the rebase process
```
