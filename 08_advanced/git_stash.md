# git stash

## What is git stash?
`git stash` temporarily saves changes in your working directory
without committing them.

It cleans your working directory so you can switch branches safely.

---


## Stash Current Changes
```bash
git stash

##View Stash List
git stash list

#Apply Stashed Changes
git stash pop

#Apply Without Removing
git stash apply

#Drop a Stash
git stash drop

##When to Use git stash
Need to switch branch quickly
Work is incomplete
You don’t want to commit yet