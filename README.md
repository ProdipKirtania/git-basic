# git-basic arranged by # Prodip Kirtania

### git basics
    git init
    git add README.md
    git add .
    git commit -m "1st commit"
    git branch -M main
    git remote add origin https://github.com/user-name/remote-repo.git
    git push -u origin main


... or push an existing repository from the command line

    git remote add origin https://github.com/user-name/remote-repo.git
    git branch -M main
    git push -u origin main


... local to remote after changes:

    git add .
    git commit -m "2nd commit"
    git push

View the commit history
-------------
> git log

> git log --oneline

remote to local
--------------------------
> git pull

How to Remove a directory from Git Repository
---------------------------------------------
>  rm -rf .git

... remove the file from the Git repository and the filesystem

    git rm file1.txt
    git commit -m "remove file1.txt"
    git push origin branch_name

... remove the file only from the Git repository and not remove it from the filesystem

    git rm --cached file1.txt
    git commit -m "remove file1.txt"
    git push origin branch_name


** All about Branch
=================================================

... Listing current branches

    git branch

... Making a new branch

    git branch [new-branch-name]

... Create a new branch and switch to it

    git checkout -b [new-branch name]

... to add new branch in remote

    git add .
    git commit -m "2nd commit"
    git push --set-upstream origin [new-branch-name]

... Switch to a branch

    git checkout [branch name]

** Merge
======================
... Merge a branch into the active branch

    git merge [branch name]

... Merge a branch into a target branch

    git merge [source branch] [target branch]

https://github.com/user-name/remote-repo.git