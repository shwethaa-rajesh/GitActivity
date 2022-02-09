

# Questions 


1. What is a VCS and why is it needed?

> VCS is version control system. VCS is used to make sure that the files in our local repository are upto date with that of the remote repository. In a team, it makes sure that there is no conflict between the code. It helps keep track of all changes made and revert to the previous versions


2. Whats is the difference between a forked repo and a cloned repo?

> Forked Repo | Cloned Repo 
  ---  |  --- 
  Forked repo creates a copy of the original repository into your github remote repo | Cloned repo clones the content of the remote repository to the local repository


3. Why do we create branches?

> Branches can be used when each person in a team has a different feature to work on. Each branch can implement a particular module/feature and a pull request can be sent to the main branch before merging

4. What is the use of fork if we can create branches?

> A branch cannot be created unless you are a collaborator. Branches are used to work on a particular feature while using a fork duplicates the whole project to the remote repository

5. Difference between Staged and unstaged changes?
>Changes that are not recorded into the version history but exist in your working directory are Unstaged changes
Staged changes have aldredy been marked which will go to our next commit ie. once we run git commit 

6. Difference between tracked and untracked files?
>A file is considered tracked if it is included in the version control.
untracked are the ones that are not included in version control and therefore any activity there is not tracked

7. How is git pull different from git fetch?
>Git fetch is used retrieve any changes from your local git. It will download all the commiits, files etc. from your remote repository to your local repository.
Git pull does what fit fetch does and merges these changes to your current branch
Therefore git fetch does fetch+merge.

8. Why do we raise PRs?
>We go to our pull requests page on our repo's page and click new pull request on the upper right.
there we can select the branch with the changes you want to submit.
and create new pull request.
On our Repo's page, 
Go to the Pull requests column, 
click new Pull request on the right hand side.
select the branch with the changes you want to submit.
then we click create pull request and then add a description to it 
click send pull request and that will submit the request.

9. What are the best practices for naming branches and writing commits?
>for naming a branch
-Specifying if its a fix, feature or a chore.
>commit message should be able to
 -tell what is done, 
 -if its a feat or chore 
 -where it is being done.
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
=======
