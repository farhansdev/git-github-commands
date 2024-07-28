# Learning Git and Github Course

# Git 
* Git is the version control system used for managing code changes locally.

# Github 
* GitHub is a platform built around Git that facilitates collaboration and provides cloud-based repository hosting.

# Most Useful Git and Github Commands
* initializing a repo = git init 
* checking the repo = git status 
* add files = git add <filename1> <filename2> ....
* adding multiple files = git add .
* removing files = git rm --cached <filename>
* comitting changes = git commit -m "first commit"
* checking file log/content = git log / git log --oneline
* checking branch = git branch
* creating new branch = git branch <branchname>
* switch new branch = git switch <branchname>
* create and switch branch in one cmd = git switch -c <branchname>
* checking branch is availble or not = git checkout <branchname>
* push code on github = git push -u origin main 
* -u for upstream, origin for = your remote repo which is in your local environment, main is your branch name in which you push your code.
when you first time pushing code on the github, you must write this command because this command set/connect your branch and remote repo on same upstream after that you can just write "git push" cmd.

# After Everytime changes you must add file and commit then you can push easily your code on github.

# Happy Coding!