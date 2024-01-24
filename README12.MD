## GIT TAG

- It is used to create a tag for a commit.

we can write the command in the following way

```bash

git tag tag_name commit_id # you can find the commit id from the git log

# if you just want to create a tag for the last commit then you can write

git tag tag_name # you can find the commit id from the git log

# to list all the tags we can write

git tag --list


# Example

git tag v1.0.0 1a2b3c4d5e6f7g8h9i0j1k2l3m4n5o6p7q8r9s0t1u2v3w4x5y6z

# to push the tag to the remote repository we can write

git push origin tag_name


```

## GIT RELEASE

- It is used to create a release for a tag. TAG is used to store the version of the project. RELEASE is used to store the version of the project with the release note.
- Tag can has small small commits but release can have large commits.

###
