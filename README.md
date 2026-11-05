# My Project

### Create a new project on your local machine, then push it your remote repo.

<img width="975" height="577" alt="image" src="https://github.com/user-attachments/assets/21725363-73b3-4748-947f-1d0ba031e34e" />

### Create two branches (dev & test) then create one file on each branch, and push this changes to the remote repo.

<img width="975" height="467" alt="image" src="https://github.com/user-attachments/assets/a3bac523-a859-40cf-9bf0-43d0a34065ed" />

<img width="975" height="845" alt="image" src="https://github.com/user-attachments/assets/508f8ef9-2123-424e-b196-b40b35fd9006" />

### Merge this changes on Main branch and then push it to your remote main branch

<img width="975" height="678" alt="image" src="https://github.com/user-attachments/assets/6945e937-5172-48a7-a0d7-13355cd7b063" />

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

<img width="975" height="170" alt="image" src="https://github.com/user-attachments/assets/b6e7eea3-9a06-486f-a29f-6905d14f81bb" />

### Push it to the remote repository.

<img width="975" height="181" alt="image" src="https://github.com/user-attachments/assets/6eed1111-a234-466c-af39-27c70b303c80" />

### Tell me how to list tags.

<img width="975" height="143" alt="image" src="https://github.com/user-attachments/assets/58eaee6f-390f-4143-b334-4060546aaf37" />

### Tell me how to delete tag locally and remotely

To delete local tags
  -	git tag -d v1.0
To delete Remote tags
  -	git push origin --delete v1.0

<img width="577" height="455" alt="image" src="https://github.com/user-attachments/assets/e5ebcd4e-6840-411f-a520-01039e7ddbb0" />

