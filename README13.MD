### GET CHECKOUT

git checkout is used to switch to another branch.

### GIT CHECKOUT TagCommitHEAD

In order to go back to a previous commit or previous tag (it can be specified by the commit id or tag name) we can use the following command:

```bash

git checkout <commit-id> # it will go to the commit id

git checkout <tag-name> # it will go to the tag name
```

##### Point of concern

- if suppose we are current on the v0.3 of a project and you tracked back to v0.1 for some reason and they made some changes in the v0.1 and you make some commits then it will create new commit Timeline and things will be messed up.

#### Delete a tag

```bash

git tag -d <tag-name>
```
