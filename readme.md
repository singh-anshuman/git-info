# GIT Guide

## Important GIT Commands

###### git init
Initializes a folder as git repository.

###### git remote add origin <REMOTE_REPO_URL>
Sets Remote Repository.
e.g.
git remote add origin https://github.com/singh-anshuman/springboot-rabbitmq-poc.git

###### git remote -v
Displays Remote Repository.

###### git reset --hard
Discards all local changes to all files permanently. This is useful when you've not even staged your changes and you want to discard all these changes.

###### git branch
Displays all the branches present locally (even if they are mapped with a remote branch).

###### git branch -a
Displays all the branches including remote branches.

###### git branch <BRANCH_NAME>
Creates a new branch locally with the given name.

###### git push -u origin <BRANCH_NAME>
Pushes newly created local branch to remote and sets remote upstream on this branch.

###### git branch -d <BRANCH_NAME>
Deletes local branch.

###### git push origin --delete <BRANCH_NAME>
Deletes remote branch.

###### git checkout <BRANCH_NAME>
Switches to a different branch.

###### git checkout -b <BRANCH_NAME>
Creates a new branch and also switches to it.

###### git merge <BRANCH_NAME>
Merges the specified branch with the currently checked out branch.
