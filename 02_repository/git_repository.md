# Git Repository and .git Folder

## What is a Git Repository?
A Git repository is a directory that Git tracks. It contains all the files of a project and the complete history of changes made to those files.

---

## What Happens When You Run `git init`?
When `git init` is executed:
- Git creates a hidden `.git` folder
- Git starts tracking the directory
- Version control becomes active

---

## 📘 Book Analogy

- Project folder = Book content
- `.git` folder = Library record room
- Commits = Published editions stored in records

If the record room is destroyed, the library forgets all history.

---

## What is Inside the `.git` Folder?
The `.git` folder contains:
- Commit history
- Branch information
- Configuration
- HEAD pointer

This folder is the heart of Git.

---

## Important Rules
- Never edit `.git` manually
- Never delete `.git` unless you want to remove Git
- `.git` is hidden by default

---

## What Happens If `.git` Is Deleted?
- Git stops working
- Commit history is lost
- Repository becomes a normal folder

---

## Commands Used
```bash
git init
ls -a
