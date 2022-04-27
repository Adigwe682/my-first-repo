# Basic Git commands
*This file contains ecery basic commands for ecerydat use*
## cloning a repo
To clone a repo we use the `git clone` command
- This command can be used to clone our repo as well as other people's repo
### The syntax
> for personal repo
```
git clone https://{personal access token}@githhub.com/usernaame/{repository}.git
```

> for other people's repo
```
git clone https://github.com/{username}/{repository}.git
```
## Staging/Adding a file
To stage or add a file for git  to track use `git add` This is used to make git track a file and follow all changes.
##The syntax
> To add one file
```
Git add Filename
```
> To add multiple file
```
Git add .
```

## Checking file status
The git commad `git status` is used to check the satus of a file. whether it have been staged or not and commited or not. Also checks the satus of working tree.
## The syntax
```
Git status
```
## Commiting a file
The commad for committing a file is ` git commit`. This is used to commit all staged file to git. a committed file can be tracked with it's automatically generated hash key for later use
### The syntax
> To just cpmmit with a message
```
git commit -m "message"
```
 - The flad *-m* stands for message with the expected message within a quotation marks
 - The message are identifies for what that commit is all about
 . To add and commit an already tarcked file
 ```
 git commit -a -m "message"
 ```
 - The *-a* is for add

## Pushing to github or any remote repo
The command `git push` is used to push our commit to any remote repositories like github or gitbucket.
### The syntax
> Repo with single branch and automatic upsteam
```
git push
```
> repo with multiple branch and non generic upstream name *i.e: origin*
```
git psuh upstream-name branch-name
```