# GitHub Beginners Cheatsheet 🚀

Welcome to the GitHub beginners cheatsheet! This guide will help you understand the most essential Git and GitHub commands.

## What is Git and GitHub?
- **Git**: A version control system that tracks changes in your code.
- **GitHub**: A cloud-based platform that hosts Git repositories and helps you collaborate with others.

---

## 🛠️ Basic Configuration
Run these commands once when you install Git to set your identity:
```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

---

## 📁 Starting a Project

**1. Initialize a new Git repository**
```bash
git init
```
*(Turns an existing folder into a Git repository)*

**2. Clone an existing repository**
```bash
git clone <repository_url>
```
*(Downloads a repository from GitHub to your computer)*

---

## ✏️ Making Changes

**1. Check the status of your files**
```bash
git status
```
*(Shows which files have been modified, added, or deleted)*

**2. Add files to the staging area**
```bash
git add <file_name>   # Add a specific file
git add .             # Add all changed files
```
*(Prepares your changes to be saved)*

**3. Commit your changes**
```bash
git commit -m "A short message describing what you changed"
```
*(Saves your changes to your local repository)*

---

## ☁️ Working with GitHub (Remote)

**1. Connect your local repo to GitHub**
```bash
git remote add origin <repository_url>
```

**2. Push your changes to GitHub**
```bash
git push -u origin main
```
*(Uploads your local commits to GitHub. `-u` sets origin main as the default for future pushes)*

**3. Pull the latest changes from GitHub**
```bash
git pull origin main
```
*(Downloads the latest changes from GitHub and merges them into your local files)*

---

## 🌿 Branching
Branches let you work on new features safely without affecting the main code.

**1. Create a new branch**
```bash
git branch <branch_name>
```

**2. Switch to a branch**
```bash
git checkout <branch_name>
```
*Or do both at once:*
```bash
git checkout -b <branch_name>
```

**3. List all branches**
```bash
git branch
```

---

## 🔄 Undoing Mistakes

**1. Discard changes in a file (before adding)**
```bash
git checkout -- <file_name>
```

**2. Unstage a file (after `git add`)**
```bash
git reset HEAD <file_name>
```

Happy Coding! 🎉
