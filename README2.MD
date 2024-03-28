### GitHub Life Cycle in Depth manner

1.  Working Directory

    1.1 Untracked Files

            ```The files which are not tracked by git are called untracked files.```
        untracted file is only tracked by git only when we add it to staging area.

    1.2 Unmodified Files

        ```The files which are tracked by git and not modified are called unmodified files.```

    1.3 Modified Files

        ```The files which are tracked by git and modified are called modified files.```

2.  Staging Area (INDEX)

    2.1 Staged Files

        The files which are added to staging area are called staged files.

        we can add files to staging area by using

        ```bash git add <file-name>```

        command.

3.  Local Repository

    `The files which are committed are called committed files.` and they are stored in local repository.

    ```bash
    # we can commit files by using

    git commit -m "commit message"
    ```

4.  Remote Repository

    `The files which are pushed to remote repository are called pushed files.`

    ```bash
    # we can push files to remote repository by using

    git push origin <branch-name>
    ```

origin/main : This specifies the remote repository and the branch name.
ans also specifies the last changes push up to which commit to the remote repository.

HEAD -> main : this specfices reference to the current branch.
