---
title: Lesson 01 - Git
---

## GitHub 

Read the [Git and GitHub documentation](https://novillo-cs.github.io/apcsa/tools/) provided in the Tools section.

## Git Commands: When to Use Them

### `git clone`
**When to use:**  
Use this the **first time** you want to copy a remote repository (e.g., from GitHub) to your computer.  

**Command:**  

`git clone <repository_ssh_url>`

**Tip:**
Run this only once per project. After that, use git pull to update your local copy.

### `git pull`

**When to use:**
Use this to bring in the latest changes from the remote repository to your local repository.

**Command:**

`git pull`

**Tip:**
Always run this before starting new work to make sure your files are up to date.


### `git add`

**When to use:**
Use this to stage (mark) new or modified files that you want to include in the next commit.

**Command:**
For one file
`git add <file_name>`
For all changes
`git add .`



### `git commit`

**When to use:**
Use this after git add to save a snapshot of your staged changes in the local repository.

**Command:**

`git commit -am "Describe the change you made"`

**Tip:**
Write clear and meaningful commit messages so you and others understand the change.


### `git push`

**When to use:** To send your committed changes from your computer to the remote repository (e.g., GitHub).

**Command:** 

`git push`


## Typical Workflow

1. `git pull`: get the latest updates.

2. Edit your code/files.

3. `git add`: if new files have been added or to stage your changes.

4. `git commit -am "message"`: save your changes locally.

5. `git push`: upload your changes to GitHub.
