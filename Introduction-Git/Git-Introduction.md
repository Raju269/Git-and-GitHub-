# Git – Beginner Friendly Documentation

What is Git?

Git is a distributed version control system (VCS) used to track changes in source code during software development. It helps developers collaborate, manage different versions of code, and roll back to previous states if needed.

Why Git is Useful

Collaboration: Multiple developers can work together and merge changes easily.

History Tracking: Revert to previous versions whenever needed.

Branching & Merging: Develop features separately and merge them safely.

Distributed Development: Each developer has a full copy of the repository.

Incremental Changes: Git stores snapshots efficiently using compression and delta encoding.

Core Concepts of Git

Before using Git, it is important to understand some core concepts.

1. Repositories

A repository (repo) is a storage space where your project files and their history are kept.

Types of Repositories

Local Repository: Stored on your local machine.

Remote Repository: Hosted on platforms like GitHub, GitLab, or Bitbucket.

2. Commits

A commit is a snapshot of your project at a specific point in time.

Each commit has a unique hash ID

Includes a message describing the change

Helps track project history

3. Branches

Branches allow developers to work independently without affecting the main codebase.

Common Branch Types

Main (or Master): Stable, production-ready code

Feature Branch: Used for new features or bug fixes

4. Merging

Merging combines changes from one branch into another.
If conflicts occur, they must be resolved manually.

5. Cloning

Cloning creates a local copy of a remote repository.

Includes all files

Includes full commit history

Includes all branches

6. Pull and Push

Pull: Fetches and merges changes from remote to local

Push: Sends local commits to the remote repository

The Three States of Git (Staging Area)

Git files exist in three states:

Working Directory

Where you edit files

Changes are not tracked yet

Staging Area

Files prepared for commit

Uses git add

Repository (.git)

Stores permanent snapshots (commits)

Uses git commit

➡️ Flow: modify → add → commit

Basic Git Commands
Command	Description
git status	Shows file status
git add <file>	Stages a file
git add .	Stages all changes
git commit -m "message"	Saves changes
git branch <name>	Creates branch
git checkout <branch>	Switches branch
git merge <branch>	Merges branches
git push origin <branch>	Pushes code
git pull origin <branch>	Pulls updates
git log	Shows commit history
Git Workflow (Step-by-Step)

Clone Repository

git clone git@github.com:username/repository.git


Create & Switch Branch

git checkout -b feature-branch


Make Changes & Stage

git add <file-name>


Commit Changes

git commit -m "Add new feature"


Push Branch

git push origin feature-branch


Create Pull Request

Merge feature branch into main on GitHub

Update Local Main

git checkout main
git pull origin main


Delete Feature Branch

git branch -d feature-branch
git push origin --delete feature-branch

Git Hosting

Git hosting platforms store repositories online and enable collaboration, backup, CI/CD, and deployment.

1. GitHub

Public & private repositories

Pull requests & code reviews

GitHub Pages

GitHub Actions (CI/CD)

2. GitLab

Built-in CI/CD

Issue tracking

Project management

Self-hosting option

3. Bitbucket

Private repositories focus

CI/CD pipelines

Jira & Trello integration

Secure team collaboration

Discussion Note

⚠️ Correction: In the Git Workflow diagram, the arrow from Staging Area → Local Repository should be labeled git commit.

🔑 Easy Summary Points (Beginner Friendly)

Git tracks changes and protects your code

Repositories store project files and history

Commits save snapshots of your work

Branches allow safe feature development

Pull gets updates, Push shares your work

Staging area controls what gets committed

GitHub, GitLab, Bitbucket host Git repositories

Git is essential for students and professionals