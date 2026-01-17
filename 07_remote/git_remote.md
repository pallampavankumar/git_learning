# Git Remote, Push and Pull

## What is a Remote Repository?
A remote repository is a Git repository hosted on a remote server such as GitHub.

It allows collaboration and backup.

---

## What is origin?
`origin` is the default name Git gives to the remote repository.

--- 


## View Remote Repositories
```bash
git remote
git remote -v

#add a git repo
git remote add origin <repo-url>

#push changes to remote
git push origin main

#first push
git push -u origin main

#pull changes
git pull

##Fetch vs Pull
git fetch → Downloads changes without merging
git pull → Fetch + merge