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

### Login by ssh-key  
ssh -T git@github.com  

### Make an empty Repo to uploade project form Local to Remote:  
git init

