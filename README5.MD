### GIT RESTORE

- git restore is used to restore the changes which are not committed.

we can use git restore in the following way:

```bash

# 👉 restore the changes which are not committed
# it will bring back the changes which are not committed and head will be on the last commit.

# it is something like undo the changes which are not committed.
git restore <file-name>

# 👉 restore the changes which are not committed with index

git restore --staged <file-name>

```

```bash

# if i will do something like git add .

git add .

# now i am working with the staging area i can apply git restore command here as well

git restore --staged <file-name>

# it will remove the file from the staging area and put it back to the working directory

# it will first compare with the last commit and then it will remove the changes in the file after the last commit.




```
