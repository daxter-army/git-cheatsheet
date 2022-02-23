# git-cheatsheet
**repository -** It is a workspace, which tracks changes, and manage files within the directory.

## 0. git config
* Check already set git user (if any):
```git config --get user.name```

* Check already set git email (if any):
```git config --get user.email```

* Set global git name/email
```git --global config user.name "Mehul Singh Teya"```
```git --global config user.email "daxter_army@gmail.com"```

## 1. basics
* ```git init``` : It will initialize a directory with git, telling it to become alive and track changes in the directory, creates a **.git** folder(hidden) in your working directory.

* ```git status``` : It displays the state of your working directory, the files that are staged for tracking, and which files are not being tracked by git.

* ```git add file_1 file_2``` or ```git add .```: Add files to the staging area, for tracking them
* ```git commit -m "your_commit_message"```: Commit changes from the staging area.

**FAQs**
### What is inside **.git** folder?
* It contains dirs like config, description, HEAD, hooks etc, contains everything from log files to remote address, which helps git to work.

























<!-- OLD -->
## git stash

## git push (to a branch)
*let branch name: **login_feature** 
git add.
git commit -m "commit_message"
git push origin

## git ammend
* with changed commit message
```sh
git add .
git --amend -m "your_new_commit_msg"
```

* with previous commit message
```sh
git add .
git --amend --no-edit
```
