# git rebase

## What is git rebase?
`git rebase` moves or reapplies commits from one branch
on top of another branch.

It rewrites commit history to make it linear.

---


## Basic Rebase
```bash
git checkout feature-branch
git rebase main

##Resolve conflict, then:
git add <file>
git rebase --continue

#Abort rebase:
git rebase --abort

##Important Warnings
Rebase rewrites commit hashes
Never rebase shared history
Safe for local feature branches only