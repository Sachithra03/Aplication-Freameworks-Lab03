# Aplication-Freameworks-Lab03

# Git Practices

## Overview
This repository contains Git practice work for Lab 03. The lab focuses on learning and applying basic Git version control concepts such as cloning a repository, creating branches, committing changes, merging branches, and pushing updates to a remote GitHub repository.

## Objectives
- Practice basic Git commands
- Understand branch creation and switching
- Commit changes properly
- Merge branches into the main branch
- Push changes to GitHub

## Git Commands Used

### Check Git Installation
git --version

### Clone Repository
git clone https://github.com/Sachithra03/Aplication-Freameworks-Lab03.git

### Check Repository Status
git status

### Add and Commit Changes
git add .
git commit -m "commit changes"

### Create and Switch Branches
git branch JS/callback
git branch JS/Promises
git branch JS/async-await
git checkout JS/callback
git checkout JS/Promises
git checkout JS/async-await

### Merge Branches into Main
git checkout main
git pull origin main
git merge JS/callback
git merge JS/Promises
git merge JS/async-await

### Push Changes to GitHub
git push origin main

## Branches Used
- main
- JS/callback
- JS/Promises
- JS/async-await

## Final Status
All feature branches were successfully merged into the main branch and pushed to the remote repository. The working tree is clean and up to date.

## Conclusion
This lab helped to gain practical experience with Git version control and understand the standard workflow used in collaborative software development.
