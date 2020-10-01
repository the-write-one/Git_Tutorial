# Forking GitHub Repositories and Creating Pull Requests

Learn to use the GitHub web application and Git command line tools to clone a Git repository, make changes and create a pull request for merging your changes into the source project.

## Pre-requisites

The following software and tools are used:

1. Chrome browser (version 85.0.4183.121).
You can use a browser of your choice to download Git.
  
2. Windows 10™ operating system.

## Logging into GitHub

GitHub is a web application and online repository based on the Git version control system.
The GitHub web application allows browsing existing repositories, and performing certain maintanence tasks
in the browser, such as creating a new repository, cloning existing repositories, making simple file changes, 
committing the changes, merging into the source (or upstream) project using pull requests, etc. 

To log into GitHub:
1. Open the link [https://github.com/](https://github.com/) in your web browser. If are already signed in, proceed to the next section.
2. To sign in, if you already have an account, choose **Sign In** from the top-left menu.
3. Enter your user name and password, click **Sign In**.

<img src="clone/01_Log_In.png" width="400">

> 💡 If you don't have a GitHub account, select **Sign In** or follow the link [https://github.com/join](https://github.com/join) to sign up.
> Enter **Username**, **Email** and **Password**, and select **Create Account**. Follow the directions to verify your email address.<br>
> <img src="clone/02_Join.png" width="400">

## Find and Fork the Test Repository

Once logged in, you should see the GitHub web page with your account icon on the right.

1. Locate the **Search or jump to...** field.

<img src="clone/03_Search.png" width="500">

2. Enter `nobl9/writingtest` in the search field and press Enter. You should see the repository in the search result.

<img src="clone/04_Find.png" width="500">

3. Click on the repository name `nobl9/writingtest` in the search results to navigate to the repository page.

<img src="clone/05_Repo_Page.png" width="500">

4. On the repository page, click on the **Fork** button on the top left. Wait for the forking process to complete.

<img src="clone/06_Forking.png" width="500">

5. Once forking is complete, you should see the `writingtest` repository under your account.

<img src="clone/07_Forked.png" width="500">

Next we will clone the forked repository on a local maching using Git command line.

## Cloning the Fork Using Git Command Line

- [Installing Git](Installing_Git.md) <br> This tutorial is intended for novice Git users and guides you through the step-by-step Git Setup Wizard. You will need to install Git to use the command line tool.

- [Setting Up SSH Key](SSH_Key.md) <br> Procedures to generate, set up an SSH key and use it with a GitHub account.

...

## Creating a Pull Request

Pull request is a mechanism to share your changes with the original project contributors and incorporate your changes in such upstream project.

1. Open the upstream repository in the browser using the link [nobl9/writingtest](https://github.com/nobl9/writingtest).

> 💡 The link to the original repository is also located in the tag line **forked from ...** on your forked repository page. (See picture at step 5 in **Find and Fork the Test Repository** above.)

<img src="clone/10_Click_Pull_Request.png" width="500">

2. Click **Pull Requests** in the repository toolbar.




Congratulations! You have successfully completed forking a GitHub repository and creating pull request.

## Resources
The following are extra resources to help you through with further information. 
1. [Getting started with GitHub](https://docs.github.com/en/free-pro-team@latest/github/getting-started-with-github)
2. [Working with forks](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/working-with-forks) in Github Docs
3. [Creating a pull request from a fork](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request-from-a-fork)


