---
sidebar_position: 1
---
# Git & Github Cheatsheet
Easy git and github cheatsheet.

### Set Username and Email
Setup author name and email. It is represented in all work.
```
git config --global user.name "yourname"
git config --global user.email "youremail"
```

### View Username and Email & Other Config
```
git config --list
```

## To Get Help
```
git help
git help <command>
```
### Clone
To download copy of repository
```
git clone <url of repository>
```
## Status
To view current status
```
git status 
```

### Init Repository
When you create new project, first you need to initalize it. If you don't initialize other commands doesn't work.
```
git init
```

### Add File To Staging Area
If you use `git add filename`, it will only add specific file to staging area. If you use `git add .`, it will add all the files to staging area.
```
git add filename or
git add . 
```

### To Commit File
When you commit, you can save the current status of file to git. It will only works on files which are in staging area.
```
git commit -m "Short Message About Work You Have Done"
```

## Check the Difference
To check difference between commited and unstaged file.
```
git diff
```

### How to Move File From Local to Remote
- Create a remote repository.
- add the origin url to command.

```
git push origin master
```
Here master is branch name.


