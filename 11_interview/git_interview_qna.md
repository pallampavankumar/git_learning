# Git Interview Questions & Answers (Beginner → Advanced)

This section covers the most commonly asked Git interview questions
with clear and practical answers.

---

## 🟢 Beginner Level

### 1. What is Git?
Git is a distributed version control system used to track changes in files
and collaborate with multiple developers efficiently.

---

### 2. What is the difference between Git and GitHub?
- Git is a version control tool
- GitHub is a platform that hosts Git repositories

Git works locally, GitHub works online.

---

### 3. What is a repository?
A repository is a directory that Git tracks, including files and their full
change history.

---

### 4. What is a commit?
A commit is a snapshot of staged changes stored permanently in Git history.

---

### 5. What is the staging area?
The staging area allows you to select which changes will be included
in the next commit.

---

## 🟡 Intermediate Level

### 6. What are Git file states?
- Working directory
- Staging area
- Repository

Files move through these states using `git add` and `git commit`.

---

### 7. Difference between `git pull` and `git fetch`?
- `git fetch` downloads changes without merging
- `git pull` downloads and merges changes

---

### 8. What is a branch?
A branch is a lightweight pointer to a commit that allows parallel development.

---

### 9. What is the difference between merge and rebase?

| Merge | Rebase |
|----|----|
| Preserves history | Rewrites history |
| Creates merge commit | Creates linear history |
| Safe for shared branches | Safe for local branches |

---

### 10. What is HEAD?
HEAD is a pointer to the current commit you are working on.

---

## 🔴 Advanced Level

### 11. What is `git stash`?
`git stash` temporarily saves uncommitted changes and cleans the working
directory.

---

### 12. What is `git cherry-pick`?
It applies a specific commit from one branch onto another branch.

---

### 13. What is an annotated tag?
An annotated tag is a full Git object that points to a commit and stores
metadata like message, author, and date. Used for releases.

---

### 14. Are tags pushed automatically?
No. Tags must be pushed explicitly using:

```bash
git push origin <tag-name>
