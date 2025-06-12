# Git Practice – 11 June 2025

## Commands Practiced
- git --version
- git init
- git add .
- git commit -m "message"
- git remote add origin <url>
- git push -u origin main

# Check Git version
git --version

# Navigate to Git practice directory
cd "/c/Users/Taranjot Singh/Desktop/CLOUD/1_Git_Practice"

# Initialize Git repo
git init

# Open folder in VS Code
code .

# Set Git global username & email
git config --global user.name "Taranjot Singh"
git config --global user.email "65taranjot@gmail.com"

# Add remote repository
git remote add origin https://github.com/Taranjot13/1_Git_Practice

# Rename default branch to main
git branch -M main

# Stage all files
git add .

# Commit the changes
git commit -m "Initial commit"

# Push to GitHub
git push -u origin main

# Check current branch
git branch

# Create a new branch
git branch <branch-name>

# Switch to a branch
git checkout <branch-name>

# Create and switch to a new branch
git checkout -b <branch-name>

# Rename current branch
git branch -m <new-name>

# Delete a branch (local)
git branch -d <branch-name>    # safe delete (if merged)
git branch -D <branch-name>    # force delete

# List remote branches
git branch -r

# Push a branch to GitHub
git push origin <branch-name>

# Pull latest changes from a branch
git pull origin <branch-name>

# Set upstream (connect local → remote)
git push -u origin <branch-name>

