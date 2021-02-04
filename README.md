# git-basic

 git basics
 ============

> git init

> git add README.md

> git add .

> git commit -m "1st commit"

> git branch -M main

> git remote add origin https://github.com/user-name/remote-repo.git

> git push -u origin main


or push an existing repository from the command line
------------------------------------------------------
> git remote add origin https://github.com/user-name/remote-repo.git

> git branch -M main

> git push -u origin main


local to remote after changes:
-----------------
> git add .

> git commit -m "2nd commit"

> git push

to check history
-------------
> git log

> git log --oneline


remote to local
--------------------------
> git pull

How to Remove a directory from Git Repository
---------------------------------------------
>  rm -rf .git

** All about Branch
=================================================

Listing current branches
-----------------------------
> git branch

Making a new branch
-----------------------------
> git branch <branch-name>

Create a new branch and switch to it
--------------------------------------
> git checkout -b [branch name]

to add new branch in remote
-------------------------------------
> git add .

>> git commit -m "2nd commit"

>>> git push --set-upstream origin [new-branch-name]

Switch to a branch
--------------------------
> git checkout [branch name]

Merge a branch into the active branch
------------------------------------
> git merge [branch name]

Merge a branch into a target branch
-----------------------------------
> git merge [source branch] [target branch]

https://github.com/user-name/remote-repo.git