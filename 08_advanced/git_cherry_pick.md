# git cherry-pick

## What is git cherry-pick?
`git cherry-pick` applies a specific commit from one branch
onto the current branch.

It copies a commit instead of merging the entire branch.

---

## 📘 Book Analogy
- Book A has many chapters
- You like only ONE chapter
- Cherry-pick = copy that one chapter into your book

---

## Basic Usage
```bash
git cherry-pick <commit-hash>

#Abort cherry-pick:

git cherry-pick --abort