<!-- Write your notes here -->
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
