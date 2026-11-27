# Session 2 Reflection

## Q1. How do issues and pull requests together support change control?

An issue records why a change is needed and what needs to be done. A pull request shows the actual changes made to address the Issue and allows the changes to be reviewed before merging. In the practical, I linked PR #2 to Issue #1 using Closes #1, which allows the change to be traced back to its original request.

## Q2. Why did the conflict in Part 4 happen, and how could a team reduce such conflicts?

The conflict happened because branch-a and branch-b modified the same line in conflict-demo.md with different deployment targets. Git could not determine which version to keep, so I had to resolve it manually. A team could reduce such conflicts by communicating their changes, assigning tasks clearly and regularly updating their branches.

## Q3. What would be lost if people merged straight into main without a pull request?

There would be no proper review process before the changes are merged into main. It would also be harder to track the reason behind a change and any discussions related to it. This could result in unwanted changes or errors being introduced into main.