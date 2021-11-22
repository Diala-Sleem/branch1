# branch

4. Add text to the readme file on the content branch. Don't forget to add and commit these changes.
5. Note that the changes in your previous branch
* git add <filename>
* git add <file1> <file2> <file3>
* git add 
* git commit -m “commit message”
    * • -m : the commit's message.
    * • -am : commits modified files.
* git status
* git log
* git log --oneline
* git checkout <commit-hash>
* git checkout master
* git branch <branch name>
* git checkout <branch name>
* git checkout -b <branch name>
* git branch
    * -r : to list remote branches
    * -a : to list remote and local branches
* git checkout master
* git branch -m <new_branch_name>
* git branch -m <old_branch_name> <new_branch_name>
* git merge <branch name>
* git branch -d <branch name>
    > NOTE : ‘-d’ means deleting the branch only if
the branch is pushed and merged with the
remote branch.
NOTE : ‘-D’ means deleting forcefully without
checking whether the branch is pushed or not
* git remote add origin <remote repository URL>
* git remote -v
* git push origin master

> ## To delete the remote branch
> * git push origin --delete <branch_name>
> * git push origin :<branch_name>

> ## To rename the remote branch by deleting
> * git push origin :<old_branch_name> <new_branch_name>




## Ignoring Files

To ignore files that you don't want to be tracked or added to the staging area, you can create a file called .gitignore in your
main project folder.
•
Inside of that file, you can list all the file and folder names that you definitely do not want to track

> .gitignore – matching pattern
