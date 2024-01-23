#### GIT STASH

- git stash is used to save something for the temporary purpose.

- git stash is used to save the changes which are not committed.

`we can use git stash in the following way`

````bash

# 👉 save the changes which are not committed

git stash

# 👉 save the changes which are not committed with message

git stash save "message"


you can use git stash in the following way:


```

### we can bring back the changes which are saved by using git stash in the following way:

```bash

# 👉 bring back the changes which are saved by using git stash

git stash pop

# 👉 bring back the changes which are saved by using git stash with index

git stash pop stash@{index}

```
````
