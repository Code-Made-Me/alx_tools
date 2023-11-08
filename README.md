# Git

## Learning Objectives

**At the end of this project, you are expected to be able to explain to anyone, without the help of Google:**

## General

*What is source code management*
Source code management, also known as version control or revision control, is a system or process used by software developers to track and manage changes to their source code and collaborate on software development projects.
It helps developers keep track of different versions of their code, manage multiple contributors, and maintain a history of changes over time

*What is Git*
Git is a distributed version control system (DVCS) that is commonly used for source code management

*What is GitHub*
is a web-based platform for hosting and managing Git repositories.

 *What is the difference between Git and GitHub*
The main difference between Git and GitHub is that Git is the version control system itself, which you install and run locally on your computer, while GitHub is a cloud-based platform that hosts Git repositories and provides additional collaboration and project management tools.

## How to create a repository

1. Install Git: If you haven't already, install Git on your local machine.
2. Navigate to your project directory using the command line or terminal.
3. Initialize a Git repository by running the following command: git init
4. You now have a local Git repository for your project.

*What is a README*
A README is a text file that provides information about your project.

## How to write good READMEs

1. tart with a clear and concise project title.
2. Provide an overview of your project's purpose and key features.
3. Include installation instructions, system requirements, and dependencies.
4. Offer examples of how to use your project, with code snippets if applicable.
5. Explain how to contribute to the project (if it's open source).

## How to commit

1. Stage your changes using the git add command. For example:
***git add filename***

2. Commit the staged changes with a descriptive message using the git commit command. For example:
***git commit -m "commit message***

## How to write helpful commit messages

1. Be concise and descriptive in your message.
2. Start with a one-line summary of the change.
3. Provide additional details in the message body if necessary.

## How to push code

1. To push code to a remote repository (e.g., GitHub), use the git push command. For example:
***git push origin main***

## How to pull updates

1. To pull updates from a remote repository, use the git pull command. For example:
***git pull origin main***

## How to create a branch

To create a branch in Git, use the git branch command. For example:

***git branch new-feature***

## How to merge branches
To merge branches, use the git merge command. For example:

***git merge new-feature***

## How to work as collaborators on a project

To work as collaborators on a project, you can follow these steps:

Clone the repository from the remote location using git clone.

Create branches for different features or bug fixes.

Make changes in your branches, commit them, and push to the remote repository.

Create pull requests on platforms like GitHub to propose changes to the main project.

Collaborate through code reviews and discussions within pull requests.

Merge changes into the main branch when they are approved.

## Which files should and which files should not appear in your repo

Files that should appear in your repository typically include source code, documentation, configuration files, and assets needed for the project to run. Files that should not appear in your repository often include sensitive data like passwords, API keys, binary files (such as compiled executables or large datasets), and generated files (e.g., build artifacts). You can use a .gitignore file to specify which files or directories to exclude from version control.

