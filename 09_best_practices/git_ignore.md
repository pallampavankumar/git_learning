# .gitignore – Complete Guide

## What is .gitignore?
`.gitignore` is a file used to tell Git which files or folders
should NOT be tracked or committed.

It helps keep the repository clean and secure.

---

## 📘 Book Analogy
- Book → Your project
- Draft notes / trash papers → Temporary files
- `.gitignore` → List of things the publisher must ignore

You don’t publish rough notes with the final book.

---

## Why .gitignore is Important
- Prevent committing unnecessary files
- Avoid committing secrets
- Keep repo clean
- Reduce noise in `git status`

---

## Common Files to Ignore
- Dependency folders (node_modules)
- Build output
- Environment files
- Logs
- IDE/editor files
- OS-specific files

---

## Basic Syntax Rules

### Ignore a file
```gitignore
.env
