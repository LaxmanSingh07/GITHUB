#### GIT STASH

- git stash is used to save something for the temporary purpose.

- git stash is used to save the changes which are not committed.

`we can use git stash in the following way`

one i use the git stash command it will save the changes which are not committed. and i will be on the last commit.

```bash

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

`we can also see the list of changes which are saved by using git stash in the following way:`

```bash

# 👉 see the list of changes which are saved by using git stash

git stash list

# 👉 see the list of changes which are saved by using git stash with graph

git stash list --graph

# 👉 we can also clear the list of changes which are saved by using git stash in the following way:

git stash clear




````

```

```

##### To apply a stash on the bases of name we can use

```bash

git stash apply stash@{name}



# or

git stash apply stash@{index}



```
