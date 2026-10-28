# Version Control and Collaboration - Assignment 1

**Student Name:** sixto espejo
**Student ID:** TCBTH2078970
**Course:** Version Control and Collaboration
**Instructor:** Michael Lewis
**Date:** October 28, 2026

---

## Overview

This repository contains my work for **Assignment 1** of the Version Control and Collaboration course. The assignment introduces the core ideas behind version control systems (VCS), with a focus on Git and GitHub, and how teams use them to build software together.

## Objectives

- Understand what version control is and why it matters
- Learn the basic Git workflow: `init`, `add`, `commit`, `status`, `log`
- Practice working with remote repositories on GitHub
- Learn branching, merging, and resolving conflicts
- Understand collaboration practices such as pull requests and code reviews

## What is Version Control?

Version control is a system that records changes to files over time so you can recall specific versions later. It lets you:

- **Track history:** see who changed what, when, and why
- **Revert mistakes:** go back to a previous working state
- **Work in parallel:** multiple people can edit the same project without overwriting each other
- **Back up work:** remote repositories keep a safe copy of the project

### Types of Version Control Systems

| Type | Description | Examples |
|------|-------------|----------|
| Local | Changes tracked on a single computer | RCS |
| Centralized | One central server holds the history | SVN, Perforce |
| Distributed | Every user has a full copy of the history | Git, Mercurial |

## Prerequisites

- [Git](https://git-scm.com/downloads) installed
- A [GitHub](https://github.com/) account
- A text editor or IDE (e.g., VS Code)

Check your Git installation:

```bash
git --version
```

Configure your identity:

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

## Basic Git Commands Used

| Command | Purpose |
|---------|---------|
| `git init` | Create a new local repository |
| `git clone <url>` | Copy a remote repository to your machine |
| `git status` | Show the state of the working directory |
| `git add <file>` | Stage changes for the next commit |
| `git commit -m "message"` | Save staged changes with a message |
| `git log` | View commit history |
| `git branch` | List, create, or delete branches |
| `git checkout -b <name>` | Create and switch to a new branch |
| `git merge <branch>` | Merge a branch into the current one |
| `git push` | Upload commits to the remote repository |
| `git pull` | Download and merge changes from the remote |

## Assignment Workflow

1. **Create a repository** on GitHub and clone it locally
2. **Add files** (this README and any required assignment files)
3. **Commit changes** with clear, meaningful messages
4. **Push** all work to GitHub
5. **Submit** the repository link
6. **log --Online and remote -v** to have the proccess number.
6. **Take screenshot and submit via team** of the 

```bash
git clone https://github.com/sixtoespe/VCC_1.git
cd <VCC_1>
git add .
git commit -m "Add README for Assignment 1"
git push origin main
```

## Collaboration Concepts

- **Branching:** isolate work on a feature or fix without affecting `main`
- **Pull Requests (PRs):** propose changes and request review before merging
- **Code Review:** teammates give feedback to improve quality
- **Merge Conflicts:** occur when two changes touch the same lines; resolve them manually, then commit
- **Issues:** track bugs, tasks, and ideas

### Good Commit Message Practices

- Use the imperative mood: "Add login form", not "Added login form"
- Keep the subject line short (about 50 characters)
- Explain *why* the change was made when it isn't obvious
- Make small, focused commits

## Repository Structure

```
.
├── README.md        # Project documentation (this file)
└── ...              # Other assignment files
```

## What I Learned

As I used Github before in my java course 6 years ago, github wasn't new for me but I forgot some comands which this course is a great refresh.

## Resources

- [Pro Git Book](https://git-scm.com/book/en/v2)
- [GitHub Docs](https://docs.github.com/)
- [Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)

---

_Submitted for Version Control and Collaboration, Assignment 1._
