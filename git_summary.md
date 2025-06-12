# 🧠 Git & GitHub Practice Summary

## ✅ Git Configuration
```bash
git config --global user.name "Taranjot Singh"
git config --global user.email "65taranjot@gmail.com"


# 📁 Repo Setup
mkdir 1_Git_Practice
cd 1_Git_Practice
git init
git remote add origin https://github.com/Taranjot13/1_Git_Practice.git
git branch -M main

# 📌 Basic Workflow
git add .
git commit -m "Your commit message"
git push -u origin main  # first time push
git push                 # next pushes

# 🔄 Pull Changes
git pull                # sync local with remote

# 🌿 Branching
git branch                    # list branches
git checkout -b new-branch    # create & switch
git switch new-branch         # switch branch (new way)
git merge branch-name         # merge into current
git branch -d branch-name     # delete branch

# 🌐 Remotes
git remote -v               # view remotes
git remote add origin <url> # add remote

# 📚 Logs and Status
git status
git log

# 💡 Extra Push Commands
git push origin branch-name         # push specific branch
git push --set-upstream origin dev  # set upstream
git push --force                    # force push