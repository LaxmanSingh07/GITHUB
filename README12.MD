## GIT TAG

- It is used to create a tag for a commit.

we can write the command in the following way

```bash

git tag tag_name commit_id # you can find the commit id from the git log

# if you will not provide any commit_id then it ill consider the current head position
# if you just want to create a tag for the last commit then you can write

git tag tag_name # you can find the commit id from the git log

# to list all the tags we can write

git tag --list


# Example

git tag v1.0.0 7567678ddxtyuyu57

# to push the tag to the remote repository we can write

git push origin tag_name

# in tag there will be zip file of the project with the tag name

```

## GIT RELEASE

In GitHub, a release is a way to package and distribute a specific version of your software or project to users. It's essentially a snapshot of your project at a particular point in time, usually associated with a specific tag or commit.

#### Steps involved in creating a release

- Go to the repository on GitHub
- Click on the releases tab
- Click on the create a new release button
- Fill out the form with the tag version, title, and description
- Click on the publish release button
