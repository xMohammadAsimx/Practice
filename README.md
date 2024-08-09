## Practising Git Commands

Step 1 - git init -- Initialize an existing directory as Git Repository (.git Folder is Created)

Step 2 - git status -- Provides information of tracked files, Currently README.md is untracked. 

Step 3 - git add "<file>" -- Starts tracking a file

Step 4 - git commit -m "your message" - Goes into staging enviroment (temporary) to help us push our file (README.md) into Github Repository.
 git co
Step 5 - git branch -M main -- Allows our branch to rename it to Main

Step 6 - git branch -- Shows the current branch.

Step 7 - git remote add origin https://github.com/xMohammadAsimx/Practice.git

Step 8 - git push origin main -- Push the code to Github from origin to main. -- Destination is origin and pushing from main

Step 9 - After making some changes you have to again git add, then check git status and the git commit and then finally push the code

Step 10 - git add . -- Make all the files that are untracked tracked.

Step 11 - Created a file .gitignore using GUI Interface of Github and then git pull origin main to our local VS Code. 

Step 12 - .gitignore -- If you want to ignore some files to be committed then you can add them in gitignore

Step 13 - We usually provide the path of folders we don't wish to push into the repository. For instance I have created a file "myenv" which I don't want to push into the repository of my github. For that proceed to .gitignore and type myenv/ this way it will not push that folder into the repository and will stop tracking that folder.

Step 14 - Now we are currently working under main* as shown with git status. In order to switch to the branch of developerA type the following in terminal "git checkout developerA" again type git status to verify your branch

Step 15 - Now after developerA updates the code and commit changes he switches to main branch as soon as he types git checkout main, he will only see the main code and not his updated code since developerA had the replica of that code. In order to merge that code to main First of all do the following

- git checkout main
- git merge developerA

Step 16 - git branch -d developerA -- Inorder to delete a local branch will delete developerA