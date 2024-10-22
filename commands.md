Git Command Reference
Directory Management
Create a directory:
mkdir git-for-devops
Print working directory:
pwd
Change directory:
cd git-for-devops
List files:
ls
List all files, including hidden files:
ls -a
File Operations
Create and edit a file:
vim hello-dosto.txt
Remove a file:
rm hello-dosto.txt
Create multiple files:
touch nibba.txt nibbi.txt
Restore a deleted file:
git restore nibba.txt
Create a new file:
touch file.txt
Git Repository Management
Initialize a new Git repository:
git init
Staging and Committing Changes
Check the status of the repository:
git status
Add files to the staging area:
git add nibba.txt nibbi.txt
Remove a file from staging:
git rm --cached nibba.txt
Commit changes with a message:
git commit -m "adding nibba"
Commit edited file:
git commit -m "edited nibba file"
Commit another file:
git commit -m "add hello-dosto file"
Commit a newly added file:
git commit -m "added new file"
Branching
Create and switch to a new branch:
git checkout -b prince
Switch to the master branch:
git checkout master
Create a branch from the master:
git checkout -b from-master
List all branches:
git branch
Viewing History
View commit history:
git log
View a condensed commit log:
git log --oneline
Configuration
Set global username:
git config --global user.name "prince9169"
Set global email:
git config --global user.email "prince.iskoolz@gmail.com"
