GIT GUIDES

------------------------------------------------------------------------------------------------
Guides Github: https://guides.github.com/
Command line guide***: https://guides.github.com/introduction/git-handbook/

Video guide git - "Git & GitHub: GitHub Workflow": 
		    https://www.youtube.com/watch?v=47E-jcuQz5c&list=PLg7s6cbtAD17Gw5u8644bgKhgRLiJXdX4&index=0

------------------------------------------------------------------------------------------------


1.Example: Contribute to an existing repository

# download a repository on GitHub.com to our machine
git clone https://github.com/me/repo.git

# change into the `repo` directory
cd repo

# create a new branch to store any new changes
git branch my-branch

# switch to that branch (line of development)
git checkout my-branch

# make changes, for example, edit `file1.md` and `file2.md` using the text editor

# stage the changed files
git add file1.md file2.md

# take a snapshot of the staging area (anything that's been added)
git commit -m "my snapshot"

# push changes to github
git push --set-upstream origin my-branch

-----------------------------------------------

2.Example: Start a new repository and publish it to GitHub

# create a new directory, and initialize it with git-specific functions
git init my-repo

# change into the `my-repo` directory
cd my-repo

# create the first file in the project
touch README.md

# git isn't aware of the file, stage it
git add README.md

# take a snapshot of the staging area
git commit -m "add README to initial commit"

# push changes to github
git push --set-upstream origin master

------------------------------------------------

3.Example: contribute to an existing branch on GitHub

# assumption: a project called `repo` already exists on the machine, and a new branch has been pushed to GitHub.com since the last time changes were made locally

# change into the `repo` directory
cd repo

# update all remote tracking branches, and the currently checked out branch
git pull

# change into the existing branch called `feature-a`
git checkout feature-a

# make changes, for example, edit `file1.md` using the text editor

# stage the changed file
git add file1.md

# take a snapshot of the staging area
git commit -m "edit file1"

# push changes to github
git push


------------------------------------------------------------
