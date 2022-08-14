# Class 3 Notes

## Git

Git intro (summarized from <https://blog.udemy.com/git-tutorial-a-comprehensive-guide/>)

Version Control allows users to maintain and different versions of files by tracking changes

** 3 versions

    1. Local - one database on a hard drive
    2. Centralized - single server with all changes
    3. Distributed - Creates multiple mirrors eliminating a single point of failure

Git is a DVCS that stores a reference, tracks changes, and prevents loss of data

### Git States and Process

![Git states](https://blog.udemy.com/wp-content/uploads/2015/08/image066.png)
[Source](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)

Add, Commit, Push (ACP)

    - Add - git add filename
        - git add * - adds all files in repo
    - Commit - git commit -m “changes made and why”
        - git commit * -commits all
    - Push - git push origin main

### Git Workflow

![Workflow](https://blog.udemy.com/wp-content/uploads/2015/08/image036.png)
[Source](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)

Working Directory: The actual files reside here.
Index: The area used for staging
Head: Points to the most recent commit

[Home](/reading-notes)
[Course 102 Notes](102-notes.md)
