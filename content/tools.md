---
layout: layouts/base.njk
eleventyExcludeFromCollections: true
---

# Piazza
This term we will be using Piazza for class discussion. The system is highly catered to getting you help fast and efficiently from classmates, and myself. I encourage you to post your questions on Piazza.

Find our class signup link [here](https://piazza.com/stuyvesant_high_school/fall2025/mks21x)

Piazza access code provided in class. If you missed it, ask the teacher.

# Google Classroom
It will be used for exit tickets only. All other assignments will be submitted on GitHub.

# Git
It is an open-source version control system that tracks changes in any set of computer files, usually used for coordinating work among programmers collaboratively developing source code during software development.

## GitHub
It is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere. 

## Repositories (Repos)
- A repository is a project folder where code, documentation, and other resources are stored.
- Repos can be public (visible to everyone) or private (visible only to specific people or organizations).
- Each repository contains all project files and the history of changes made to those files.

## Markdown & Documentation

GitHub supports Markdown for writing formatted documentation, which is commonly used in README files to explain projects. [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/).

## Installing Git
**Mac and Linux:** Git should be installed already.

**Windows:** Install git and the shell gitbash from [here](https://gitforwindows.org/). This includes git, gitbash, and has shell integration so that you can right-click on a folder in Windows Explorer to access gitbash at that location.

## Git commands
**The git config command:** Configuring user information used across all local repositories. The following commands set a name and an email address that are associated with each version history.

```
git config --global user.name "YOUR_NAME_HERE"
git config --global user.email YOUR_EMAIL_HERE
```

The basic commands we are going to use in this class are:

- **git clone:** Retrieve an entire repository from a hosted location via URL.
- **git pull:** Fetch and merge any commits from the tracking remote branch.
- **git add:** Add a file as it looks now to your next commit (stage).
- **git commit:** Commit your staged content as a new commit snapshot.
- **git push:** Transmit local branch commits to the remote repository branch.
- **git diff:** Displays diff of what is changed but not staged.

You may take a look at the git reference [sheet](https://education.github.com/git-cheat-sheet-education.pdf).

## GitHub Account & GitHub   Classroom Assignment

1. If you already have a GitHub account, log in. If not, please create one at [GitHub](https://github.com/). You may use any email address to sign up.

2. Accept the GitHub Classroom assignment for this class. Click [here](https://classroom.github.com/a/7uOc3gJB)

3. After accepting the assignment, click **"Add a README"**. In the file, write your name and then click **"Commit changes…"**

## Connect to GitHub with SSH

Secure Shell (SSH) is a way to safely connect to another computer (such as GitHub or a server) over the internet. It uses special keys to make sure both sides are who they say they are, and it creates an encrypted connection so no one else can see the information being shared.

Two keys are needed:

**Private key:** must be on your computer.

**Public key:** must be placed on the other device (GitHub, server) so it can recognize your computer.


Follow these steps to create an ssh key, connect to GitHub using SSH, and clone your repository.

1. Create your ssh key: Open your terminal and type

    `ssh-keygen -t ed25519`

    Check if your key was generated:
    ```
    cd .ssh/
    ls
    ```
    You should see your private key (eg. `id_ed25519`) and public key (eg. `id_ed25519.pub`) inside that directory.

2. In your GitHub account.

    Click your profile picture in the top-right corner. From the dropdown menu, select [Settings](https://github.com/settings/keys).

    In the left sidebar, click SSH and GPG keys, then click New SSH key.

    Enter a title for the key, keep the type set to Authentication Key, and paste your public key (content inside the file id_ed25519.pub) into the field "Key". Make sure you do not add spaces or blank lines.

3. Go to the following [link](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/testing-your-ssh-connection) and test your SSH connection.

4. Let's clone your repository on your local computer:

    Go to your assignments repository that you accepted for this class in GitHub (assignments repo must be accepted only once). You will see a green button, "Code". You must click on that button and select SSH to have the appropriate link that will allow you to clone your repository and copy the link you see there.

5. Create a folder `APCSA_1` anywhere in your computer.
   
6. On your terminal, go inside the folder `APCSA_1` to clone your repository and type:
    ```
    git clone PASTE_THE_LINK_YOU_COPIED_FROM_GITHUB_(git@...)
    ```

7. Go inside the folder that appears after you execute the clone command, and you will see the files you have on your GitHub repository.
