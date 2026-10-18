# Git Tutorial

Welcome to my **Git Tutorial Repository!** 🚀

This repository contains the Git commands, examples, and practice files that I used while learning **Git and GitHub**.

The purpose of this repository is to document my learning journey, practice version control, and build a strong understanding of Git commands.

## 📌 About This Repository

I created this repository while following Git tutorials and practicing different Git commands.

It includes basic and intermediate Git concepts such as:

- Initializing a Git repository
- Tracking and committing changes
- Creating and switching branches
- Merging branches
- Working with remote repositories
- Pushing and pulling changes
- Managing temporary changes using Git Stash
- Viewing commit history

## 🛠️ Git Commands and Examples

### 1. Check Git Version

Check whether Git is installed on your system.

`git --version`

### 2. Configure Git

Set your Git username and email address.

`git config --global user.name "Your Name"`

`git config --global user.email "you@example.com"`

View your Git configuration:

`git config --list`

### 3. Initialize a Repository

Create a new Git repository in your current directory.

`git init`

This command creates a hidden `.git` directory that stores the repository's version control information.

### 4. Check Repository Status

`git status`

This command displays the current state of your working directory and staging area.

It helps identify modified, staged, and untracked files.

### 5. Add Files to Staging Area

Stage a specific file:

`git add filename.txt`

Stage all changes in the current directory:

`git add .`

The staging area allows you to select which changes will be included in your next commit.

### 6. Commit Changes

`git commit -m "Initial commit"`

A commit saves a snapshot of the staged changes in your Git repository.

### 7. View Commit History

`git log`

View a simplified commit history:

`git log --oneline`

This displays previous commits along with their commit IDs and messages.

### 8. Create and Manage Branches

List all local branches:

`git branch`

Create a new branch:

`git branch feature-branch`

Switch to another branch:

`git switch feature-branch`

Create and switch to a branch simultaneously:

`git switch -c new-feature`

Branches allow developers to work on different features without directly modifying the main branch.

### 9. Merge Branches

Switch to the main branch:

`git switch main`

Merge another branch into it:

`git merge feature-branch`

Merging combines changes from different branches.

### 10. Git Stash

Temporarily save uncommitted changes:

`git stash`

View saved stashes:

`git stash list`

Reapply the latest stash without removing it:

`git stash apply`

Reapply and remove the latest stash:

`git stash pop`

Git Stash is useful when you need to switch tasks without committing unfinished work.

### 11. Connect to GitHub

Connect your local repository to a remote GitHub repository:

`git remote add origin https://github.com/username/repository.git`

Check configured remotes:

`git remote -v`

### 12. Push Changes to GitHub

Push your main branch to GitHub:

`git push -u origin main`

For subsequent pushes:

`git push`

### 13. Pull Changes from GitHub

`git pull origin main`

This command fetches changes from the remote repository and integrates them into your current branch.

### 14. Clone a Repository

`git clone https://github.com/username/repository.git`

This command downloads an existing Git repository to your local system.

### 15. Check File Differences

View unstaged changes:

`git diff`

View staged changes:

`git diff --staged`

These commands help you review modifications before committing them.

## 💻 Example Git Workflow

Below is a simple example of how I practice Git commands.

**Step 1: Initialize a repository**

`git init`

**Step 2: Create a file**

`echo "Hello Git" > hello.txt`

**Step 3: Check repository status**

`git status`

**Step 4: Stage the file**

`git add hello.txt`

**Step 5: Commit the changes**

`git commit -m "Added hello.txt"`

**Step 6: Create a new branch**

`git switch -c practice-branch`

**Step 7: Modify the file**

`echo "Learning Git and GitHub" >> hello.txt`

**Step 8: Stage and commit the changes**

`git add .`

`git commit -m "Updated hello.txt"`

**Step 9: Switch back to the main branch**

`git switch main`

**Step 10: Merge the practice branch**

`git merge practice-branch`

*Note: This example assumes the default branch is named `main`.*

## 🎯 Learning Objectives

Through this repository, I aim to:

- Understand how version control works.
- Become comfortable using Git commands.
- Learn how to manage branches and commits.
- Understand GitHub collaboration workflows.
- Practice resolving merge conflicts.
- Improve my development workflow.
- Build a foundation for contributing to open-source projects.

## 📈 Future Learning Goals

As I continue learning Git and GitHub, I plan to explore:

- Git Rebase
- Git Reset and Revert
- Merge Conflict Resolution
- GitHub Pull Requests
- GitHub Issues
- GitHub Actions
- Open-source Contribution Workflows

## 📚 Conclusion

This repository represents my progress in learning Git and GitHub through hands-on practice.

I will continue updating it as I explore new commands, concepts, and workflows.

---

⭐ **Learning Git one commit at a time!**
