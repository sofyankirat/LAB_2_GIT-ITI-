# My Project

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
