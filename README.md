# How-to-make-a-Repository

### Downloads:
- Download git from here : https://git-scm.com/

### STEPS :
- Make an empty repositroy in your account.
- Then open command prompt and open the file/folder path in cmd, which you want to add. (using `cd`)
- Now type all the below code lines to add folder/file to your repository.
****

The git init command creates a new Git repository           
 ```
 git init
 ```     
 The git status command displays the state of the working directory and the staging area                
 ```
 git status       
 ```
Below `git add .` command adds every file in that folder
```
git add .
```      
Below command adds a particular from that folder
```
git add -m "file name"
```
The commit command performs a commit, and the -m "message" adds a message
```
git commit -m "first commit"
```
Default branch is master, change it according to your default branch
```
git branch -M master
```
The git remote add command will create a new connection record to a remote repository       
```
git remote add origin <link of your repository>
```
Below command pushes the changes to the remote repository
```
git push -u origin master
```
                       

****

### Tutorial :
```
git init    
git status     
git add .                
git commit -m "How To Create a Repository"          
git branch -M master          
git remote add origin https://github.com/WiTheR60334/How-to-make-a-Repository
git pull origin master  
git push -u origin master 
```
