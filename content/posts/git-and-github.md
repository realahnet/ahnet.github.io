---
title: "An Introduction to Git and GitHub"
date: "2025-11-12"
draft: false
description: "In this blog, we'll look at Git and GitHub with their real-world applications."
showToc: true
tags: ["git", "github"]
---

![Git Cover Photo](https://media.licdn.com/dms/image/v2/D4D12AQFS_42v39bhsA/article-cover_image-shrink_720_1280/article-cover_image-shrink_720_1280/0/1675016970735?e=2147483647&v=beta&t=9c2zQlKEcKJmEUgiVj-WH6SyNGMttabxrIlZ99HbttI)

## Introduction

Git is one of the most important and popular tools used by developers today. It helps teams manage changes without losing track of progress or creating conflicts. In this post we'll explore the fundamentals of Git and GitHub and look at their real-world applications.

## What is Git?

Git is a version control system that lets you save snapshots of your code, known as commits, so you can track changes in your project over time.

Git also makes it easy to create separate versions of your work using branches, try out your code at various points, and revert to earlier states if needed. By connecting your repository to a remote service like GitHub, Git also enables smooth collaboration without conflicting changes.

## History of Git

Git was created by Linus Torvalds in 2005 after the Linux kernel team lost access to the version control system they used (BitKeeper). It was designed to handle large, distributed projects efficiently and allow developers to work together without conflicts.

Over the years, Git has grown into one of the most widely used tools in software development, being used in projects of all kinds across many different fields.

---

## How Git Works

### Repositories

A repository is like a space where all the files and their history are stored. On your computer, you work in the working directory, where you edit files, and when you’re ready to save changes, you move them to the staging area. From there, you create a commit, which is like taking a snapshot of your project at that moment, with a descriptive message explaining the changes. A new repository is initialized by the command:

```
git init
```

### Staging Changes

The staging area is a waiting area for your changes until you have added them into Git. Git doesn't automatically stage your changes. Use:

```
git add <file>
```

This lets you carefully choose which changes to commit. Multiple commits can be made from different staged sets of changes.

### Commits

Commits are snapshots of your code that record the changes at a particular point. Once your changes are staged, create a commit with:

```
git commit -m "message here"
```

### Branches

A branch is a separate version of your code that diverges from a common point. Branches allow developers to work independently and merge changes when ready.

---

## What is GitHub?

GitHub is an online platform where repositories are pushed to. It is one of the most popular Git hosting services, where many famous open-source projects reside.

GitHub makes collaboration and project management easier: you can create remote repositories, submit pull requests for code review, track progress and bugs through issues, and use built-in tools to work with teams efficiently. GitHub also supports automated testing and deployment of your code via GitHub Actions.

## Should You Learn Git?

Yes. Learning Git is essential for developers. It allows collaboration without conflicts, tracks history, and enables contributions to open-source projects.

## Practical Example

If you have a portfolio website, you can host it on GitHub Pages — a free service for static sites.

1. **Create a GitHub repository**
2. **Configure your username and email:**

```
git config --global user.name "user-name-here"
git config --global user.email "user-email-here"
```

3. **Initialize your local repository:**

```
git init
```

4. **Link your local repository to GitHub:**

```
git remote add origin repo-url
```

5. **Stage your files:**

```
git add .
```

> *Note: using `.` adds all files in the folder.*

6. **Create a commit:**

```
git commit -m "message-here"
```

7. **Push changes to GitHub:**

```
git push -u origin branch-name
```

Your code should now be on GitHub!

---

# Summary

Git and GitHub are powerful tools for managing code and collaborating with others. Git tracks changes and maintains project history, while GitHub enables sharing, contributing, and automating workflows.  

Mastering Git provides confidence and access to real-world development projects. The more you practice, the more natural version control becomes.

---