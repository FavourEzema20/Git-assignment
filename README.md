# GIT, GITHUB AND VERSION CONTROL

## Explain Version Control.

Version control also known as Source Code is a system that records changes to a file or set of files over time so that specific versions can be recalled later. It is an essential practice in software development and other collaborative projects, enabling teams to manage updates to source code and other digital assets without overwriting each other's work or causing conflicts.

## Difference between Git and GitHub.

Git is an open-source, local version control system (VCS), WHILE GitHub ia a web-based cloud platform that hosts Git repositories and adds collaboration features.

Git is installed and runs locally on your computer(offline functionality). WHILE GitHub is hosted on the web(requires an internet connection for most operations).

## GitHub Alternatives:

Git Lab: It is a web-based DevSecOps platform that allows software development teams to plan, build, and ship secure code all in one application.

Bitbucket: It is a Git-based code hosting and collaboration tool designed for teams. It provides a space where a team can collaborate on code from concept to cloud, create quality code through automated testing, and confidently deploy code.

Gitea: it is a painless self-hosted all-in-one software development service that includes Git hosting, code review, team collaboration, package registry, and CI/CD. It is similar to GitHub, Bitbucket, and GItLab.

## Differences between Git fetch and Git pull.

Git fetch is used to fetch all changes from the remote repository to the local repository WHILE Git pull is used to fetch all changes from the remote repository to the current working directory.

In Git fetch the repository data is updated in the .git directory WHILE In Git pull the working directory is updated directly.

In Git fetch there is no possibility of merge conflicts WHILE In Git pull merge conflicts are possible if the remote and local repositories have done changes at the same place.

In Git fetch Review of commits and changes can be done WHILE In Git pull Updates the changes to the local repository immediately.

## Git rebase and the command for it

Git rebase is an action in Git that allows you to rewrite commits from one Git branch to another branch.

### Command for Git rebase:

- git checkout develop
- git rebase main

## Git cherry-pick and the command for it

Git cherry-pick allows you to apply a specific commit from one branch onto another without merging the entire branch.

### Command for cherry-pick:

- git cherry-pick <commit-hash>
