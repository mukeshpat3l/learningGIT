# learningGIT

Date: 21-02-2019Learning Git with Bucky the besr guy eva!

cd .. //to backward
cd e: //to chnage the Drive
pwd //to get where you are
ls //to get list of files
ls -la //all files with hidden as well


Git Workflow
Working Copy > Staging area > Repository

git init //to initialise  
git status //to get the list of unstaged files
 - Changes to be committed (Files added using git add command)
 - Changes not staged for commit (modified: <filenname>) 
 - Untracked files (Files NOT added using git add command)
 
git add . //add all files to ready to get commited - Stage area
git add <file name> //add specific file to ready to get commited - Stage area
git commit -m "commit message" //to commit with message
git commit -am "commit message" //to commit by skiping the staging area 
git log //list of the commit 
git log --author="mukesh" //get list of commit by mukesh
git diff //to find the difference between working copy and Repository
git diff --staged //to find the difference between staged copy and Repository
git rm <file name> //to remove any file from the repo
git mv <file 1 name> <rename file name> //to rename any file instantly
git mv <file name> <Folder name> //to move file from one folder to another
git mv <file name> <Folder name>/<rename file name> //to move file from one folder to another with Rename
git checkout -- <file name> //Copy this file from repo and replace to working copy
git reset HEAD <file name> /Remove this file from staging area

