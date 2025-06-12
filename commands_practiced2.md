# Git & GitHub Essentials – Summary

## ✅ 1. Git Basics
- `git init` → Initialize local repo
- `git config` → Set username and email
- `git add .` → Stage all files
- `git commit -m "message"` → Commit changes
- `git remote add origin <url>` → Link to GitHub
- `git push -u origin main` → Push code to GitHub

---

## 🌿 2. Branching
- `git branch` → List branches
- `git checkout -b new-branch` → Create + switch
- `git switch main` → Switch branch
- `git merge new-branch` → Merge changes

---

## 🧠 3. Merge Conflicts
- Happens when two branches modify same lines
- Resolve manually:
  1. Edit conflicted file
  2. `git add .`
  3. `git commit`

---

## 📦 4. Git Stash
- Temporarily saves uncommitted work
- Commands:
  - `git stash` → Save
  - `git stash list` → View
  - `git stash pop` → Restore + delete
  - `git stash apply` → Restore only

---

## 🧹 5. Git Clean
- Deletes **untracked** files (not staged)
- Commands:
  - `git clean -n` → Preview
  - `git clean -f` → Delete

---

## 📄 6. .gitignore
- Prevents files from being tracked
- Examples:


---

## ⏪ 7. Revert vs Reset
- `git revert <commit>` → Undo safely (creates new commit)
- `git reset`:
- `--soft` → Keep changes
- `--hard` → Discard all

---

## 👥 8. GitHub Collaboration
- **Fork → Clone → Branch → Commit → Push → PR**
- Learn how to:
- Create Pull Requests
- Do Code Reviews

---

## 🏷️ 9. Tagging
- Add version tags to commits
```bash
git tag v1.0
git tag -a v1.1 -m "Version 1.1"
git push origin v1.0


## 🏷️ 10.SSH Setup (GitHub)

Copy code
ssh-keygen -t rsa -b 4096 -C "email@example.com"