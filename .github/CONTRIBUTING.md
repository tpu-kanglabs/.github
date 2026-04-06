# Contributing Guide

This document explains how to contribute to the repository.

Please [create a GitHub account](https://docs.github.com/en/get-started/start-your-journey/creating-an-account-on-github) in advance and [set up Git](https://docs.github.com/en/get-started/getting-started-with-git/set-up-git) on your local machine.

## Reporting Issues

To report a bug or other problem in the repository, create an Issue. Issues are an important tool for discussing and resolving problems related to the repository.

**Note**: If the issue involves a vulnerability, please do **not** report it through an Issue. Be sure to contact the maintainers directly.

1. Go to the repository page.
2. Click the "Issues" tab in the top menu.
3. Click the "New issue" button.
4. Fill in the title and details of the issue. For bug reports, please also include steps to reproduce and the expected behavior.
5. Click the "Submit new issue" button to create the issue.

## Proposing Changes

### 1. Fork the Repository

First, fork the repository to your own account.

1. Go to the repository page.
2. Click the "Fork" button in the upper right corner of the screen.

### 2. Clone the Repository

Clone the forked repository to your local machine.

1. Go to the page of the forked repository in your GitHub account.
2. Click the "Code" button and copy the URL displayed.
3. Open a terminal and run the following command:
    
    ```bash
    git clone <copied-URL>
    ```
    

### 3. Create a New Branch

Before making changes, create a new branch off the `main` branch.

1. Navigate to the repository directory in your terminal:
    
    ```bash
    cd <folder-name>
    ```
    
2. Create and check out a new branch:
    
    ```bash
    git checkout -b <new-branch-name>
    ```
    

### 4. Make Changes

Make the necessary changes to the project. Once your changes are complete, commit them.

If there are instructions such as running tests, be sure to follow them.

1. Stage your changes:
    
    ```bash
    git add .
    ```
    
2. Commit your changes:
    
    ```bash
    git commit -m "Short description of changes"
    ```
    

### 5. Push to the Remote Repository

Push your local changes to your GitHub repository.

1. Run the following command:
    
    ```bash
    git push origin <branch-name>
    ```
    

### 6. Create a Pull Request

Create a Pull Request on GitHub to propose your changes to the original repository.

1. Go to your GitHub repository page.
2. Click the "Compare & pull request" button.
3. Describe your changes and click the "Create pull request" button.

### 7. Code Review and Feedback

Once the pull request is created, the repository maintainers will perform a code review. If there is feedback, make the requested changes and push again.

If you have any questions or concerns, feel free to open an issue. We look forward to your contributions! 🌟