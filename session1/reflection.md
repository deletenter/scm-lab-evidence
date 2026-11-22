# Part 5: Reflection and evidence

## Q1. Why is a commit history useful when maintaining software?

A commit history helps developers keep track of changes made throughout software development. For example, if a bug appears after an update, developers can compare previous commits to identify which change introduced the bug. In my `scm-lab-evidence` repository, I can refer to my earlier commits to identify what was changed and restore a previous version if needed.

## Q2. Explain the difference between Git and GitHub.

Git is a version control tool used to track and manage changes locally, while GitHub is an online platform used to store and share Git repositories. In the GitHub Skills exercise, I used GitHub to manage branches and pull requests. Meanwhile, in `scm-lab-evidence`, I used Git to manage my local changes before pushing them to GitHub.

## Q3. What risk does working on a branch and using a pull request reduce?

Working on a separate branch reduces the risk of introducing errors directly into the `main` branch. A pull request allows changes to be reviewed before they are merged. This helps maintain the stability of the `main` branch while allowing developers to work independently.

## Q4. Which commands changed only your computer and which changed GitHub?

Commands such as `git init`, `git add`, `git commit`, `git clone` and `git pull` changed only my local environment. Meanwhile, `git push` updated the remote repository on GitHub. This shows that committing changes locally does not automatically update GitHub until the changes are pushed.

## Part 1: Concept Table

| Term | Definition |
|---|---|
| Repository | A project that contains files, folders and their version history. |
| Working tree (working directory) | The folder where I make changes to my project files. |
| Staging area (index) | An area where I prepare my changes before committing them. |
| Commit | A saved version of my staged changes. |
| Branch | A parallel version of my repository where I can work separately. |
| Merge | Combining changes from one branch into another. |
| Remote | A reference to another repository, such as my repository on GitHub. |
| Push / Pull / Clone | Push uploads my commits, pull retrieves and incorporates remote changes, and clone creates a local copy of a repository. |