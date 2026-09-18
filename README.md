# Simple Git Version Control Project

## Project Description

This is a simple practice project for learning **Git and GitHub version control**.

The project demonstrates how to:

* Create and use Git branches
* Make commits
* Push changes to GitHub
* Merge branches
* Create and resolve merge conflicts
* Pull changes from a remote repository

## Technologies Used

* Git
* GitHub
* VS Code
* HTML

## Git Workflow

The basic workflow used in this project is:

```text
Create Branch
     ↓
Make Changes
     ↓
Commit Changes
     ↓
Push Branch
     ↓
Merge Branch
     ↓
Resolve Conflicts
     ↓
Push Final Changes
```

## Example Branches

* `main` — Main project branch
* `feature-header` — Changes to the home page
* `feature-contact` — Changes to the contact page

## Basic Git Commands

### Check the status

```bash
git status
```

### Create a branch

```bash
git checkout -b feature-header
```

### Switch to a branch

```bash
git checkout mainor master
```


### Commit changes

```bash
git add .
git commit -m "Add home page"
```

### Push a branch to GitHub

```bash
git push -u origin feature-home
```

### Merge a branch

First switch to the main branch:

```bash
git switch main
```

Then merge:

```bash
git merge feature-home
```

## Resolving a Merge Conflict


To resolve the conflict:

1. Open the file.
2. Decide which changes you want to keep.
3. Remove the conflict markers.
4. Save the file.
5. Add the resolved file:

```bash
git add .
```

6. Complete the merge:

```bash
git commit -m "Resolve merge conflict"
```

7. Push the changes:

```bash
git push origin main
```


