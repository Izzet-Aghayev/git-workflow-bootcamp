# Git Cheat Sheet

## Repository Setup
```bash
git init
git clone https://github.com/Izzet-Aghayev/git-workflow-bootcamp.git

## Branching
git branch
git checkout -b feature/branch-name
git checkout main

## Status and Add
git status
git add .
git add <file>

## Commit
git commit -m "feat: add new feature"
git commit -m "fix: fix bug"
git commit -m "chore: update configs"

## Push and Pull
git push origin branch-name
git pull origin main

## Merge
git merge main
git merge feature/branch-name
