## 1-How to Delete Files Locally and Remotely in Git

### 1. Delete Files Locally
- Open the project folder on your local machine and delete them.

### 1. Delete Files remotly
- Push the change to Remote Repository

## 2-How to list tags
To list all tags in your local repository, use the following command:
```bash
git tag
```

## 3-How Delete a Tag Locally and Remotely
### 1-Delete a Tag Locally
To delete a tag from your local repository, use:
```bash
git tag -d <tagname>
```

### 2-Delete a Tag Remotaly
To delete the tag from the remote repository, first, delete it locally (as shown above). Then, run:
```bash
git push origin --delete <tagname>
```

## 4-What is Git Rebase?
git rebase is a command used to reapply commits on top of another base tip. It is commonly used to keep a clean, linear project history by integrating changes from one branch into another.

## 5-image
![Alt text](./img/gb.jpg)






