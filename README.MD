As a developer, it's hard to maintain your peoject source code.

- `Different versions`
- `History about code changes`
- `Project source code backup`
- `Sync code changes with team mates`

### Why we need git?

- Hard Disk Crash or failure
- Hard for multiple developers to work on same project
- Hard to maintain different versions of project
- Difficult to Track Changes (Versions)
- Storing proejct on Online Repository
  Easy to share
  Easy to Access (Anywhere) (if you have internet connection)
  Easy to track

### What is git?

- Git is a free and open source `distributed version control system` designed to handle everything from small to very large projects with speed and efficiency.

#### Different types of Version Control System

- Centralized Version Control System (CVCS)
  - SVN
  - CVS
- Distributed Version Control System (DVCS)
- Local Version Control System (LVCS)

#### Some git Command

```bash

# command written below used to set the user name and email address for git

git config --global user.name "Your Name"
git config --global user.email "

git init
```

`History of git`

- Git was created by Linus Torvalds in 2005 for development of the Linux kernel, with other kernel developers contributing to its initial development.

##### Life Cycle of File in git

Working Directory -> Staging Area -> Local Repository -> Remote Repository

###### Working Directory

- Working Directory is the directory where you are working on your project.

###### Staging Area

- Staging Area is the area where you add your files to be committed.

###### Local Repository

- Local Repository is the area where you commit your files.

###### Remote Repository

- Remote Repository is the area where you push your files.

#### Some very Common git command

```bash

# 👉 Initialize git in your project

git init

# 👉 Add files to staging area

git add <file-name>

# 👉 Add all files to staging area

git add .

# 👉 Commit your changes

git commit -m "commit message"

# 👉 Check status of your project

git status

# 👉 Check history of your commits

git log

# 👉 Check history of your commits in one line

git log --oneline

# 👉 Check history of your commits in one line with graph

git log --oneline --graph

# 👉 Check history of your commits in one line with graph and all branches

git log --oneline --graph --all

👉 Check history of your commits in one line with graph and all branches with date

git log --oneline --graph --all --date=short


# 👉 Rname 'master' branch to 'main' branch

git branch -m master main # m is for move

# 👉 Check all branches

git branch

# 👉 Create new branch

git branch <branch-name>

# 👉 Switch to another branch

git checkout <branch-name>

# 👉 Create new branch and switch to that branch

git checkout -b <branch-name>

# 👉 Merge branch

git merge <branch-name>

# 👉 Delete branch

git branch -d <branch-name>


# 👉 Add remote repository

git remote add origin <remote-repository-url>

# 👉 Push your code to remote repository

git push -u origin <branch-name> # u is for upstream

# 👉 Pull code from remote repository

git pull origin <branch-name>
```

`.git` this folder is hidden folder that contains all the information about your project. (i.e. history of your commits, branches, etc.)
