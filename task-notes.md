# 📘 Git Interview Notes

## 1. What is Git?
Git is a distributed version control system that allows multiple developers to track changes in source code during software development. It helps manage code versions, collaborate with teams, and roll back to previous states if needed.

---

## 2. What is the difference between Merge and Rebase?

| Feature | Merge | Rebase |
|--------|-------|--------|
| History | Creates a new merge commit | Rewrites commit history |
| Simplicity | Easier and safer | More complex |
| Use Case | When history integrity matters | When you want a clean linear history |

---

## 3. What is a Pull Request?
A Pull Request (PR) is a GitHub feature where a contributor notifies team members that they have completed a feature and requests that it be merged into another branch (usually main or dev). It supports code review and discussions.

---

## 4. How do you resolve Merge Conflicts?
Merge conflicts occur when two branches change the same part of a file differently. To resolve:
1. Git will mark the conflict in the file.
2. Manually edit the file to fix the conflict.
3. Add the resolved file using git add
4. Commit the merge using git commit

---

## 5. What are Git Tags?
Tags in Git are used to mark specific points in history as important, typically to mark a release version like v1.0.  
There are two types:
- Lightweight tags (like a bookmark)
- Annotated tags (stored as full Git objects)

---

## 6. What is Git Workflow?
Git Workflow defines how developers use Git in collaboration. Popular workflows:
- *Feature Branch Workflow*
- *Git Flow*
- *Forking Workflow*
Each workflow defines how branches are used, how changes are reviewed and merged.

---

## 7. Explain git stash
git stash temporarily saves uncommitted changes without committing them. It's useful when you need to switch branches quickly without losing your current work.
- git stash saves your changes
- git stash pop restores them

---

## 8. What is the use of .gitignore?
.gitignore tells Git which files or folders to ignore in a project.  
Example files to ignore:
- node_modules/
- .env
- *.log

This prevents unnecessary or sensitive files from being committed to the repository.

---
