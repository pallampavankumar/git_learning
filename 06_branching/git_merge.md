# Git Merge

## What is git merge?
`git merge` is used to combine changes from one branch into another.

Typically, changes from a feature branch are merged into the main branch.

---

## Types of Merge

### 1️⃣ Fast-Forward Merge
Occurs when the target branch has no new commits.

```bash
git checkout main
git merge feature-branch
