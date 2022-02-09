<!-- Write your notes here -->

11. Can we add a new remote to our repo, if yes, what is the command?
> Yes, we can add a new remote to our repo.
The command to do so is :- git remote add <REMOTENAME> <URL> 
We can change the url set to the remote name using :- git remote set-url <REMOTENAME> <URL>
we can view the reomote connections set-up using :- git remote -v 

12. Write git commands to view status of changes and the commit history.
> git status - to view the current status of the working branch
  git add - to add files to be tracked by git
  git commit - to commit the files in the staging area along with a message
  git log - to view the history the commits made and by whom along with the commit messages

13. List the basic linux commands that you learnt and write their uses.
> mkdir - create a new directory
  touch - create a new file
  ls - list out the files present in the folder
  ls -a - list out hidden files along with the non-hidden files
  rm - delete a file
  rm -rf - delete a folder
  cd - change directory
  cd .. - go back to the previous directory

14. How to sync your changes in local repository to remote one?
> For the changes made in the local repository to be synced with remote ones, we first have to ensure  that the branch is clean, to avoid future inconsistencies. 
We can reflect the changes on remote repository using the command 
git push origin <BRANCHNAME> 
