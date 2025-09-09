---
title: HW 04 - Git commands practice
due_date: 2025-09-10
---

The objective of this homework is to create a java file, add it, commit and push to a remote repository.

1. In your local machine at home, go to the folder where your assignments repo was cloned `...../APCSA1/apcsa-assignments-fall-YourUsername/`, execute `git pull` and **create a folder homework**.
2. Create a folder 09_09_welcome inside the homework folder.
3. Write a java file **Welcome.java** (this should be the path **`...../APCSA1/apcsa-assignments-fall-YourUsername/homework/09_09_welcome/Welcome.java`**). In this program, you should introduce yourself. Print two lines to the console using the System.out.println() method.

In the first line, state your name, and in the second line state your favorite hobby.

Your output should be in the following form:

```
My name is ...
My favorite hobby is ...
```

4. Run `git status`. What does it show?
5. To add the new file to the repository, run the following command from the root (top-level, `...../APCSA1/apcsa-assignments-fall-YourUsername/`) of your repo, not from inside the homework folder:

   `git add homework/09_09_welcome/Welcome.java`

6. Run `git status` again. What does it show this time?
7. Commit and push the file to your repo.
8. Go to GitHub, Welcome.java should be there.
9. Tomorrow, we will pull the changes using the lab machines.
