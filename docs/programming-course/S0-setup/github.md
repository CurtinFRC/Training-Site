# Git and GitHub Guide

## Table of Contents
1. [Git Basics](#Git Basics)  
2. [GitHub Basics](#GitHub Basics)  
3. [Naming Commits](#Naming Commits)  
4. [Creating Good Issues and PRs](#Creating Good Issues and PRs)  
5. [Workflow](#Workflow)  

---

## Git Basics

To start off with learning Git have a read of [this](https://docs.wpilib.org/en/stable/docs/software/basic-programming/git-getting-started.html) article from the WPILib team detailing some of the basic features of Git.

TODO make practice excer

## GitHub Basics

TODO add images idk
Now that we have a basic idea of common Git commands we need to learn a bit more about GitHub. GitHub is the software we will use to colloborate on code projects, such as robot code. There are a couple of key features you'll want to get familiar with early on, pull requests and issues. Issues are the primary method we use to track bugs or feature requests. They have lots of features for organisation such as milestones, labels and assignees. If you are interested in tackling an issue on one of our projects you should assign yourself to it before starting work. Pull requests are similar to issues in a lot of ways (such as organisation features) but are directly linked to a branch and its code. These are how we will do code review. You can also link pull requests to issues allowing us to see what should be ready to be tested. To get more familiar with these features we will do an excersise.

Instructor to make example repo for this
1. Open an issue
2. Assign yourself to someone elses issue
4. Open a PR with your name in a file and link it to the issue
5. Close review someone elses PR.

## Naming Commits
TODO

## Creating Good Issues and PRs
TODO

## Workflow

TODO fancy diagrams and images or smth idk
Whenever working on something, be it a feature or bug we should follow a standard workflow. This will ensure seamless collaboration within the team. On 4788 our workflow for tackling an issue looks like this:

1. Assign yourself to the relevant issue
2. Make sure your local master branch is up to date
3. Create a branch from master named first-name/issue
4. Implement feature
5. Commit feature
6. Push your branch
7. Ensure CI is passing
8. Ensure you're still up to date with master
9. Open a PR (make sure to link it to the isssue)

After opening a PR you should recieve a review from the programming captain or mentors. Make sure to implement any feedback your given and keep the PR up to date with the master branch. You can work on multiple features at the same time but they need to be on seperate branches.
