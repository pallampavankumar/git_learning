# Git Tags

## What is a Git Tag?
A tag is a reference to a specific commit, usually used to mark release points.

Tags are commonly used for versioning.

---


## Types of Tags

### Lightweight Tag
```bash
git tag v1.0

#Annotated Tag
git tag -a v1.0 -m "First stable release"

#List Tags
git tag

#Push Tags to Remote
git push origin v1.0

#Push all tags:
git push origin --tags