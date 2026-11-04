# Git Workflow Guide

This document explains the basic Git workflow used to manage project changes and collaborate with other developers.

## 1. Initialize a Repository

Use the following command to initialize Git in a project directory:

```bash
git init
```

This creates a local Git repository.

## 2. Check Repository Status

```bash
git status
```

This displays the current branch and the status of modified, staged, and untracked files.

## 3. Create and Switch Branches

Create a feature branch:

```bash
git branch feature/example
```

Switch to it:

```bash
git switch feature/example
```

Branches allow developers to work on different features independently.

## 4. Stage and Commit Changes

Stage a specific file:

```bash
git add filename
```

Commit the staged changes:

```bash
git commit -m "docs: describe the changes"
```

Meaningful commit messages make project history easier to understand.

## 5. Connect a Remote Repository

```bash
git remote add origin <repository-url>
```

This connects the local repository to a remote GitHub repository.

## 6. Push Changes

```bash
git push -u origin feature/example
```

This publishes the feature branch to GitHub.

## 7. Create a Pull Request

A Pull Request allows developers to propose changes from one branch to another.

After reviewing the changes, the branch can be merged into the main branch.

## Conclusion

Following a structured Git workflow helps maintain organized project history, supports collaboration, and makes code changes easier to review.