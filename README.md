# Hello World
<p style="font-size:21px">Follow this Hello World exercise to get started with GitHub.</p> 

## Introduction

GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.<br><br>This tutorial teaches you GitHub essentials like repositories, branches, commits, and pull requests. You'll create your own Hello World repository and learn GitHub's pull request workflow, a popular way to create and review code.<br><br>In this quickstart guide, you will:<br><br>
- Create and use a repository
- Start and manage a new branch
- Make changes to a file and push them to GitHub as commits
- Open and merge a pull request <br><br>

To complete this tutorial, you need a  [GitHub account](https://github.com/) and Internet access. You don't need to know how to code, use the command line, or install Git (the version control software that GitHub is built on). If you have a question about any of the expressions used in this guide, head on over to the [glossary](https://docs.github.com/en/get-started/quickstart/github-glossary) to find out more about our terminology.

## Creating a repository
A repository is usually used to organize a single project. Repositories can contain folders and files, images, videos, spreadsheets, and data sets -- anything your project needs. Often, repositories include a README file, a file with information about your project. *README* files are written in the plain text Markdown language. You can use this [cheat sheet](https://www.markdownguide.org/cheat-sheet/) to get started with Markdown syntax. GitHub lets you add a README file at the same time you create your new repository. GitHub also offers other common options such as a license file, but you do not have to select any of them now.<br><br>Your `hello-world` repository can be a place where you store ideas, resources, or even share and discuss things with others.

1. In the upper-right corner of any page, use the  drop-down menu, and select New repository.
Drop-down with option to create a new repository <br><br>
 ![create repository](https://docs.github.com/assets/cb-11427/images/help/repository/repo-create.png "create repository")
2. In the Repository name box, enter `hello-world`.
  
3. In the *Description* box, write a short description.

4. Select Add a *README* file.

5. Select whether your repository will be *Public* or *Private*.

6. Click Create repository.<br><br>
![click create repository](https://docs.github.com/assets/cb-106613/images/help/repository/hello-world-repo.png "click create repository")

## Creating a branch

Branching lets you have different versions of a repository at one time. <br> <br> By default, your repository has one branch named `main` that is considered to be the definitive branch. You can create additional branches off of `main` in your repository. You can use branches to have different versions of a project at one time. This is helpful when you want to add new features to a project without changing the `main` source of code. The work done on different branches will not show up on the `main` branch until you merge it, which we will cover later in this guide. You can use branches to experiment and make edits before committing them to `main`. <br><br> When you create a branch off the `main` branch, you're making a copy, or snapshot, of `main` as it was at that point in time. If someone else made changes to the `main` branch while you were working on your branch, you could pull in those updates. <br> <br> This diagram shows: <br> <br>
- The `main` branch 
- A new branch called feature 
- The journey that feature takes before it's merged into `main` 

![The journey that feature takes before it's merged into main](https://docs.github.com/assets/cb-23923/images/help/repository/branching.png "github brancing")

Have you ever saved different versions of a file? Something like:

- `story.txt`
- `story-edit.txt`
- `story-edit-reviewed.txt`

Branches accomplish similar goals in GitHub repositories.<br> <br>
Here at GitHub, our developers, writers, and designers use branches for keeping bug fixes and feature work separate from our `main` (production) branch. When a change is ready, they merge their branch into `main`.


## Create a branch

1. Click the Code tab of your `hello-world` repository.
2. Click the drop down at the top of the file list that says **main**.<br><br>
![creating branch](https://docs.github.com/assets/cb-6252/images/help/branch/branch-selection-dropdown.png "creating branch")<br><br>
3. Type a branch name, readme-edits, into the text box.
4. Click Create branch: readme-edits from main.<br><br>
![naming the branch](https://docs.github.com/assets/cb-27383/images/help/repository/new-branch.png "naming the branch")<br><br>

Now you have two branches, `main` and `readme-edits`. Right now, they look exactly the same. Next you'll add changes to the new branch.

## Making and committing changes

When you created a new branch in the previous step, GitHub brought you to the code page for your new `readme-edits` branch, which is a copy of `main`. <br> <br>You can make and save changes to the files in your repository. On GitHub, saved changes are called commits. Each commit has an associated commit message, which is a description explaining why a particular change was made. Commit messages capture the history of your changes so that other contributors can understand what you’ve done and why.<br><br> 
1. Under the `readme-edits` branch you created, click the *README*.md file.
2. Click  to edit <img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/solid/pen.svg" width="20" height="20">
 the file.
3. In the editor, write a bit about yourself. Try using different Markdown elements.
4. In the Commit changes box, write a commit message that describes your changes.
5. Click Commit changes.<br><br>
  ![first commit](https://docs.github.com/assets/cb-75044/images/help/repository/first-commit.png "first-commit")
<br><br>

These changes will be made only to the README file on your `readme-edits` branch, so now this branch contains content that's different from `main`.
  
