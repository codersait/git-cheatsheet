# list branches
## Lists all local branches.
* git branch
----------------------------------------------------------------------
# all branches
## Lists all remote and local branches.
* git branch -a
----------------------------------------------------------------------
# remote branch details
## Lists all remote branches including statuses and latest commits.
* git branch -v
----------------------------------------------------------------------
# remote branches
## Lists all remote branches.
* git branch -r
----------------------------------------------------------------------
# add new branch
## Creates a new branch based of the one currently checked out.
* git branch new-branch-name
----------------------------------------------------------------------
# create and checkout branch
## With this single command you create and checkout a new branch.
* git checkout -b new-branch-name
----------------------------------------------------------------------
# checkout branch
## Checkout an existing branch by name.
* git checkout your-branch-name
----------------------------------------------------------------------
# Push branch to remote.
* git push origin branch_name
----------------------------------------------------------------------
# Rename current branch.
* git branch -m new_name
----------------------------------------------------------------------
# Delete a local branch.
* git branch -d branch_name
# Delete a remote branch.
* git push origin :branch_name