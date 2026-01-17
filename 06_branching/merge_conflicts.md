# Git Merge Conflicts

## What is a Merge Conflict?
A merge conflict occurs when Git cannot automatically merge changes
because the same part of a file was modified differently in two branches.

Git stops and asks the developer to decide.

---


## When Do Conflicts Occur?
- Same file edited in multiple branches
- Same lines modified differently
- Branches diverged significantly

---

## How Git Shows a Conflict

```text
<<<<<<< HEAD
Code from current branch
=======
Code from incoming branch
>>>>>>> feature-branch
