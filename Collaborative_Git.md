---
id: 09_Collaborative_Git
aliases: []
tags: []
---

# 09 - Collaborative Git

[[Tags/FOSS]]
[[Tags/Workshops]]
[[Tags/Git]]

> [!IMPORTANT]
> LINK: [GitHub Repository](https://github.com/godi-png/Example_Repo)

## Why use Git for Collaboration?

- Supports parallel development through branches, enabling team members to,
work on different features simultaneously without interfering with each other

- Git's branching and merging capabilities facilitate a structured and
organized approach to collaborative development, making it easy to manage
feature developments and bug fixes

- Every collaborator has a local copy of the entire project history, allowing
them:
  - Work offline
  - Commit changes
  - and synchronize with others when connected

- Centralized remote repositories (Github, Gitlab) provide a shared space for
collaboration, allowing seamless sharing of:
  - Code
  - Tracking Issues
  - and Managing project workflows

- The pull request feature in Git platforms simplifies the process of:
  - Proposing
  - Reviewing
  - and Merging code changes
- This fosters a collaborative and transparent environment

- Integrated code review features in Git platforms allow team members to:
  - Provide feedback
  - Catch errors
  - and Maintain code quality
- ... before changes are merged into the main codebase.

- Git's commit history provides a detailed audit trail, making it easy to trace
who made specific changes, when, and why, which enhances accountability and
transparency

- Git efficiently handles large projects, making it suitable for collaborations
involving extensive codebases, multiple contributors, and diverse project
structures

- Integration with CI/CD systems enables automated testing and deployment,
ensuring that changes are validated and deployed seamlessly into the project

## Remote Repositories

- Remote Repositories are centralized repositories hosted externally, often
on platforms like:
  - GitHub
  - GitLab
  - Bitbucket
  - (*Covered in Previous Git Workshop)

- The purpose of Remote Repositories is to facilitate collaboration by serving
as a shared space for team members to push, pull, and synchronize code changes

- Developers clone a remote repository to create a local copy on their machine
to edit, change, and then add back to the remote repository

## Remote Git Credentials

- If you are using HTTPS to clone repositories, you will need a way to store
your credentials (username and personal access token) so it doesn't
consistently ask you every time you go to push updates

- You have several options to use, but the suggested manager is Git Credential
Manager, which is available on every platform and will cache your credentials
automatically

- Alternatively, GitHub has it's own command line utility called GitHub CLI
which can be installed to manage credential caching.

## Setup & Authenticating

- Create a github account (maybe with school email)

- Install gh cli and set up
  - `gh auth login -w`

- Login through the web

## How to Install Git Credentials Manager

- MacOS (Using Homebrew)

- Windows
  - The GitHub installer has been archived since Jul 15, 2023

- Linux
  - Distribution package manager

## Cloning

- Cloning is the process of creating a local copy of a remote repository. This
is useful for collaboration and working on projects

- Allows developers to work on projects collaboratively by providing a copy of
the entire project's history and files on their local machine

- Remote Repositories:
  - Typically hosted on platforms like GitHub, GitLab, or Bitbucket

- Benefits:
  - Enables offline work on the project
  - Facilitates parallel development with branches
  - Provides a complete version history for reference
