# Simple CLI Commands

Below is a list of CLI commands that we'll use occasionally

## Working with files folders

''' bash

# Creating a folder
mkdir <folder name>

# Creating a file

touch <file name>

# Navigating through files

cd 

# navigating one step back

cd ..

# Navigating back to the root folder

cd ~

# Removing files and folders that have no permisssions
rm <file/folder name>

# Removing files or folders that have permissions
rm -rf <file/folder name>

# Opening a folder in vs code
code <folder/file name/current directory>

# List files within a folder(unhidden)
ls

# List files within a folder(with hidden)
ls -a

## Basic git commands

'''bash

# initialise a local .git repository
git init

# Connect a local repository to a github repo
git remote add origin

# Add changes made to a local repository
git add .

# Set/confirm the changes made(without messege)
git commit 

# Set/confirm the changes made(with messege)
git commit -m "<messahe here>"

# Upload commited work to github
git push

# Make a new branch
git branch <branch name>

# List branches
git branch -a

# Change to a different branch
git checkout <branch name>

# Check status of local repository
git status

# Download existing repo from github
git clone

# Undo local changes to the state of a Git repo
git reset





