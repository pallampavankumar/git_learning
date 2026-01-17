# Git Tags

## What is a Git Tag?
A tag is a reference to a specific commit, usually used to mark release points.

Tags are commonly used for versioning.

# Git Annotated Tags – Complete Guide

## What is an Annotated Tag?
An annotated tag is a full Git object used to mark important points in history,
such as releases (v1.0, v2.0).

Unlike lightweight tags, annotated tags store:
- Tag message
- Tagger name and email
- Tag creation date
- Optional GPG signature

Annotated tags are recommended for production releases.

---

## Lightweight Tag vs Annotated Tag

| Feature | Lightweight Tag | Annotated Tag |
|------|----------------|---------------|
| Git object | ❌ No | ✅ Yes |
| Message | ❌ No | ✅ Yes |
| Tagger info | ❌ No | ✅ Yes |
| Date | ❌ No | ✅ Yes |
| GPG signing | ❌ No | ✅ Yes |
| Recommended for releases | ❌ | ✅ |

---

## Does a Tag Point to the Current Commit?
Yes.

By default, a tag always points to the **current commit (HEAD)**.

```bash
git tag -a v1.0 -m "First stable release"



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

##Tag a Specific Commit
You can tag any commit using its hash:
git tag -a v1.0 <commit-hash> -m "First stable release"

#Push a single tag
git push origin v1.0

#Push all tags
git push origin --tags

#List all tags
git tag

#View detailed tag information
git show v1.0

#Delete tag locally
git tag -d v1.0

#Delete tag from remote
git push origin --delete v1.0