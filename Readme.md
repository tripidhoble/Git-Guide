### Git commands for Reference:

#### To set origin 
  * git remote set-url origin <clone-url-from-gitlab>
 
#### To create new branch and switch to new branch
  * git checkout -b <new_branch_name>
    
    OR
  * git branch <new_branch_name>
  * git checkout <new_branch_name>

#### get list of all branches
  * git branch -a
  
#### clone git repo
  * git init
  * git clone <URL>
 
#### This creates a new branch new-branch, based on existing-branch.
  * git checkout -b new-branch existing-branch
  
#### To check if a local repo is up to date with remote:
  * git remote show origin
   
#### To commit
  * git commit -m "my commit"
   
#### To edit the previous commit instead of new commit
  * git commit --amend -m "updating new changes in previous commit"

#### To push the changes in local file(whict are commited) on remote
  * git push origin <branch_name>
   
#### Discard any local changes which are not committed in ALL branches and master
  * git checkout -f
#### To delete local branch
  * git branch -D branch_name
 
#### To pull a certain branch from GitHub/Remote
  * git pull origin other-branch

