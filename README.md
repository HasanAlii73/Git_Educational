# Git_Educational  

### Add local folder to Repo:  
git clone https:\www.github.com\Myskf...  
  
### Check the folder status:
git status   
  
### 1- Add the changes from working directory to staging area:  
git add . \ git add fileName  
  
### unAdd the changes from working directory to staging area:
git reset head fileName  
  
### 2- Add the changes from staging area to local Repo:  
git commit -m "Message"  
  
### 3- Add the changes from local Repo ot remote Repo:  
git push RemoteName RemoteBranch  
  
### Get the branch name:  
git branch  

### Get the Remote Branch name:  
git remote -v  

### Get the changes from Remote to Local:  
git pull origin  

### Generate Public Key:  
ssh-keygen -t rsa -b 4096 -C "ha133@gmail.com"  

### Login by ssh-key:  
ssh -T git@github.com  

### Make an empty Repo to uploade project form Local to Remote:  
git init

### Make an Alias:  
git config --global alias.st status  

### Make new branch:  
git branch branchName  

### Switch to Branch:  
git checkout branchName  

### Safe Delete branch:  
git branch -d branchName  

### Forced Delete branch:  
git branch -D branchName  

### Make new branch and Switch to it:  
git checkout -b branchName  

### Rename branch:  
git branck -m branchName  

### Save the changes in the Stash:  
git stash  

### Get the Stash list:  
git stash list  

### Extact from the Stash:  
git stash pop  

### Save the changes in the Stash with a Message:  
git stash save "the Message"  

### Extact from the Stash and Keep the Stash:  
git stash apply  

### Extact from a specific Stash:  
git stash pop stash@{2}   

### Delete Stash:  
git stash drop stash@{1}  

### Get the stash content:  
git stash show  

### Delete all stashes:  
git stach clear  

### unStage changes (unAdd):  
git restore --staged fileName

### Show the unSataged files you will Delete:  
git clean -n

### Delete the unSataged files:  
git clean -f  