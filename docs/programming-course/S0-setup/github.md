# GitHub Guide

## Table of Contents
1. [Introduction](#introduction)  
2. [Prerequisites](#prerequisites)  
3. [Getting Started](#getting-started)  
    - [Installing Git](#installing-git)  
    - [Configuring Authentication](#configuring-authentication)  
4. [Basic Workflow](#basic-workflow)  
    - [Cloning a Repository](#cloning-a-repository)  
    - [Creating a Branch](#creating-a-branch)  
    - [Committing Changes](#committing-changes)  
    - [Pushing Changes](#pushing-changes)  
5. [Collaboration](#collaboration)  
    - [Pull Requests](#pull-requests)  
    - [Code Review](#code-review)  
6. [Advanced Features](#advanced-features)  
7. [Best Practices](#best-practices)  
8. [Troubleshooting](#troubleshooting)  
9. [Additional Resources](#additional-resources)  

---

## Introduction
Brief overview of GitHub and its key features.

## Prerequisites
- Git installed (v2.x or later)  
- GitHub account  
- Command-line familiarity  

## Getting Started

### Installing Git
1. Download from https://git-scm.com/  
2. Follow installer prompts.

### Configuring Authentication
- Generate SSH key:  
  `ssh-keygen -t ed25519 -C "you@example.com"`  
- Add public key in GitHub → Settings → SSH and GPG keys.

## Basic Workflow

### Cloning a Repository
```bash
git clone git@github.com:username/repo.git
```

### Creating a Branch
```bash
git checkout -b feature/your-feature
```

### Committing Changes
```bash
git add .
git commit -m "Describe changes"
```

### Pushing Changes
```bash
git push origin feature/your-feature
```

## Collaboration

### Pull Requests
1. Open a PR on GitHub.  
2. Assign reviewers and labels.  
3. Address feedback and merge.

### Code Review
- Use inline comments.  
- Approve or request changes.

## Advanced Features
- GitHub Actions (CI/CD)  
- Releases & tags  
- Issue templates & workflows  

## Best Practices
- Write clear commit messages.  
- Keep branches focused.  
- Use descriptive PR titles.

## Troubleshooting
- Common Git errors and solutions.  
- Links to GitHub Help.

## Additional Resources
- Official Docs: https://docs.github.com/  
- Interactive Tutorial: https://try.github.io/  
- Cheat Sheet: https://education.github.com/git-cheat-sheet-education.pdf  