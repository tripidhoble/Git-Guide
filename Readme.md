Git commands for Reference:

#### To create new branch and switch to new branch
  * git checkout -b <new_branch_name>
    
    ** OR
  * git branch <new_branch_name>
  * git checkout <new_branch_name>

#### This creates a new branch new-branch, based on existing-branch.
  * git checkout -b new-branch existing-branch
  
#### To check if a local repo is up to date with remote:
  * git remote show origin
   
#### To commit
  * git commit -m "my commit"
   
#### To edit the previous commit instead of new commit
  * git commit --amend -m "updating new changes in previous commit"
   
#### Discard any local changes which are not committed in ALL branches and master
  * git checkout -f

