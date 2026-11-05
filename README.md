# My Project

### Create a new project on your local machine, then push it your remote repo.

### Create two branches (dev & test) then create one file on each branch, and push this changes to the remote repo.

### Merge this changes on Main branch and then push it to your remote main branch

### Tell me how to remove them locally and remotely.

Locally:

  - git branch -d dev
  - git branch -d test

and we use -D to the force remove

Remote:

  - git push origin --delete dev
  - git push origin --delete test

  we must to be in the main branch before the removal

### Tell me how to checkout another branch without commit changes 

By using git stash command 

  - git stash
  - git checkout firstbranch
  - git checkout secondbranch

### Create an annotated tag with tagname (v1.7) .

### Push it to the remote repository.

### Tell me how to list tags.

### Tell me how to delete tag locally and remotely
