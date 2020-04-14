
# learningGIT

Phase 1 -> Date: 21-02-2019 Learning Git
Phase 2 -> Date: 11-04-2020 Learning Git with Bucky the best guy eva!

## Basic Git commands
1. cd .. //to backward
2. cd e: //to chnage the Drive
3. pwd //to get where you are
4. ls //to get list of files
5. ls -la //all files with hidden as well


## Git Workflow
Working Copy > Staging area > Local Repository > Remote Repository

## Git Credentials
git config --global user.name "Firstname Lastname" //configure the user which will be used by Git
git config --global user.email //configure the email address


## Basic Git Commands:
1. `git init` //to initialize  
2. `git status` //to get the list of upstaged files
 - Changes to be committed (Files added using git add command)
 - Changes not staged for commit (`modified: <filenname>`) 
 - Untracked files (Files NOT added using git add command) 
3. `git add .` //add all files to ready to get committed - Stage area
4. `git add <file name>` //add specific file to ready to get committed - Stage area
5. `git commit -m "commit message"` //to commit with message
6. `git commit -am "commit message"` //to commit by skipping the staging area 
7. `git log` //list of the commit 
8. `git log --author="mukesh"` //get list of commit by mukesh
9. `git diff` //to find the difference between working copy and Local Repository
10. `git diff --staged` //to find the difference between staged copy and Local Repository
11. `git rm <file name>` //to remove any file from the repo
12. `git mv <file 1 name> <rename file name>` //to rename any file instantly
13. `git mv <file name> <Folder name>` //to move file from one folder to another
14. `git mv <file name> <Folder name>/<rename file name>` //to move file from one folder to another with Rename
15. `git checkout -- <file name>` //Copy this file from Local Repository and replace to working copy
16. `git reset HEAD <file name>` //Remove this file from staging area
17. `git remote` //to check linked remote repo
18. `git remote add <repoNickName> <repoURL>` //To link the remote repo

https://github.com/dictcp/awesome-git