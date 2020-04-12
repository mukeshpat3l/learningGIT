# learningGIT

Date: 21-02-2019Learning Git with Bucky the besr guy eva!

1. cd .. //to backward
2. cd e: //to chnage the Drive
3. pwd //to get where you are
4. ls //to get list of files
5. ls -la //all files with hidden as well


Git Workflow
Working Copy > Staging area > Repository

1. git init //to initialise  
2. git status //to get the list of unstaged files

 - Changes to be committed (Files added using git add command)
 - Changes not staged for commit (modified: <filenname>) 
 - Untracked files (Files NOT added using git add command)
 
3. git add . //add all files to ready to get commited - Stage area
4. git add <file name> //add specific file to ready to get commited - Stage area
5. git commit -m "commit message" //to commit with message
6. git commit -am "commit message" //to commit by skiping the staging area 
7. git log //list of the commit 
8. git log --author="mukesh" //get list of commit by mukesh
9. git diff //to find the difference between working copy and Repository
10. git diff --staged //to find the difference between staged copy and Repository
11. git rm <<file name>> //to remove any file from the repo
12. git mv <<file 1 name>> <<rename file name>> //to rename any file instantly
13. git mv <<file name>> <<Folder name>> //to move file from one folder to another
14. git mv <<file name>> <<Folder name>>/<<rename file name>> //to move file from one folder to another with Rename
15. git checkout -- <<file name>> //Copy this file from repo and replace to working copy
16. git reset HEAD <<file name>> /Remove this file from staging area

