## Commit Timeline

`commit is nothing but an object or snapshot` which contains the following properties:

- `commit id`
- `author`
- `message`
- `parent commit id`
- `timestamp`
- `changes`
- `branch name`
- `tag name`
- `remote name`
- `remote branch name`

`The first commit ` is known as the `root commit` and it doesn't have any parent commit id.

`every commit not store all the information but only the changes made in that commit.` otherwise the size of the repository will be very large.

`all the commits are stored in .git/objects folder` and the name of the commit is the `commit id`.

`all the commits stores the parent commit id except the root commit`.

###### How to know that changes i did in the file ?

```bash
git diff
# this command shows the difference between working directory and staging area.(current version and the last commit version)

# i can also compare between two commits by using there commit id's

git diff <commit-id-1> <commit-id-2>





```
