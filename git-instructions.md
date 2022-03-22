# Git Basic Instructions

![alt text](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)   

[Credits](https://tutorialzine.com/2016/06/learn-git-in-30-minutes)
1. Configuring Git
2. > `git config --global user.name "My Name"`   
   > `git config --global user.email` myEmail@example.com
3. Creating a new repository (move to the folder using cd and type
   > `git init`
4. Checking the status  
   > `git status`
5.  **Staging Area** 
    > `git add -A` (add all the files) or
    > `git add "file.format"` (add specific file)
6.  Commiting the repository
    > `git commit -m "Message."`
7.  Connecting to a remote server
    > `git remote add origin https://...`
8. Uploading to a server
    > `git push origin master`
9. Cloning a repository
    > `git clone https://...`
10. Getting changes from the server
    > `git pull origin master`
11. Create new branches
    > `git branch branch_name`
12. Switch to branch
    > `git checkout branch_name`
13. Merging branches
    > `git checkout master`
    > `git merge branch_name`
14. Delete a branch
    > `git branch -d branch_name`
15. Checking difference between commits
    > `git log`
16. Reverting a file to a previous version
    > `git checkout logid filename.format`
17. Fixing a commit
    > `git revert HEAD` or `git revert logid`
18. Remove an origin (Git Page)
    > `git remote rm origin`