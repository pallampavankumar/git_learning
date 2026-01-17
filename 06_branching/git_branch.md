# Git Branching Basics

## What is a Branch?
A branch is a lightweight pointer to a commit.
It allows you to work on features independently without affecting the main code.

---

## Why Branches Exist
- Develop features in isolation
- Fix bugs safely
- Experiment without breaking main code

## Default Branch
The default branch is usually called `main`.
It represents the stable version of the project.

---

## Common Branch Commands

### List branches
```bash
git branch

# create a branch
git branch feature-login

#switch branch
git checkout feature-login

#create and switch
git checkout -b feature-signup

##What Happens When You Switch Branches?

    Files change to match the branch

    HEAD moves to the new branch

    Commits go to the current branch only