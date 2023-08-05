<h1 align="center">Git and GitHub</h1>

<p align="center">
<img src="https://skillicons.dev/icons?i=git,github" />
</p>

## Index

- [What is Git](#what-is-git)
- [What is GitHub?](#what-is-github)
- [Features of Git and Github](#features-of-git-and-github)
- [What is a Repository]()

## What is [Git](https://git-scm.com/)

Git is a [distributed](https://git-scm.com/about/distributed) version control system (VCS). It's a system that keeps a record of changes to our project files over time. It enables us to record project changes and go back to a specific version of the files, at any given point in time. This system can be used by many people to efficiently work together and **collaborate on team projects**, where each developer can have their own version of the project, distributed on their computer. Later on, these individual versions of the project can be merged and adapted into the main version of the project.

Basically, it's a massively popular tool for coordinating parallel work and managing projects among individuals and teams. Needless to say, knowing **`how to use Git is one of the most important skills for any Software Developer nowadays`** - and it's definitely a great addition to your resume!

## What is [GitHub](http://github.com)?

GitHub is a hosting platform for Git repositories. You can use Git on its own without Github (and other similar platforms), but it's difficult without github to collaborate or share your code with others.

- **Git is the version control system, the tool that tracks changes to our files over time**
- **Github is a hosting service for projects that use Git.**

Using _GitHub_, we can upload a local project repository to a remote cloud-based GitHub repository. We can also interact with public repositories published by other developers.

ℹ️ GitHub could even be looked at as a social networking website for developers. Users can follow each other, give ratings, share or fork, like code via stars, comment via issues, collaborate and communicate.

GitHub allows developers to utilize, change or improve software from its repositories. Each repository contains all project files and the code history. Repositories can have multiple collaborators and can be either public or private.

GitHub is also a popular way developers to publish their project portfolio online. It's an easy way to showcase skills and experience to potential employers or clients. It's an important technology to be familiar with, especially for a new developer who is just starting out.

### Features of Git and Github

1. **Version Control:** Git keeps a record of every change you make to your project, so it has the ability to remember every change you make to your code. It's like time-travel! So, if you make a mistake you can easily go back to a previous version if you need to.

1. **Sharing with Friends:** You can share your code with your friends or anyone around the world, and they can marvel at your creations, give suggestions, take inspiration, or even add their own touches to your works.

1. **Collaboration:** . Multiple people can work together on the same project simultaneously, and Git helps merge everyone's work seamlessly and makes it effortless for everyone to contribute their parts.

1. **Backup:** Git Repository ensures safety and protects your work from getting lost or damaged. Even if your computer misbehaves, your projects are securely stored and can be accessed from another computer.

### What is a Repository

**A Git repository is a container for a project that is tracked by Git.**

Imagine a repository as a special place that stores your creative project, just like a treasure chest for your computer code and files. Git repository is a magical box that keeps track of every change you make to your code and files over time. The Repository is like your personal storage area in the digital world. It helps you keep track of your code, artworks, or any other digital wonders you create. Instead of saving your work scattered all over your computer, you place everything inside this repository.

We can single out two major types of Git repositories:

- **Local repository** - an isolated folder stored on your own computer, where you can work on the local version of your project.
- **Remote repository** - generally stored outside of your isolated local system, usually on a online server i.e [github.com](https://github.com). It's especially useful when working in teams, this is the place where you can share your project code, see other people's code and integrate it into your local version of the project, and also push your changes to the remote repository.

### What is CLI Tools

CLI (command-line interface) allows you to interact with a computer using text-based commands instead of relying on Graphical user interfaces (GUIs), the CLI provides a powerful and efficient way to perform various tasks and operations directly from the Terminal also called shell. All terminals work almost similarly, CLI tools offer efficiency, flexibility, and scripting capabilities, making them powerful resources for developers, system administrators, and tech-savvy users.

Types of terminals:

- Bash
- Command prompt or CMD
- PowerShell

Git is a CLI Tool, which we can access with our system terminals. **🔴 All commands will be ran on the root of the project source directory**.

## [Staging files](https://git-scm.com/about/staging-area)

We can use the **git add** command to add our files to the staging area, which allows them to be tracked.

We can add a specific file to the staging area with the following command:

```bash
git add file.js
```

To add multiple files, we can do this:

```bash
git add file.js file2.js file3.js
```

Instead of having to add the files individually, we can also add all the files inside the project folder to the staging area:

```bash
git add .
```

By default, this adds **all the files and folders** inside the project folder to the staging area, from where they are ready to be committed and tracked.

## Commits

`git add` will stage the files that will be part of my commit

tip: make small commits

A **commit** is a snapshot of our code at a particular time, which we are saving to the commit history of our repository. Commit is like page in history book that has its own unique id and can never be changed.

After adding all the files that we want to track to the staging area with the **`git add`** command, we are ready to make a commit.

To commit the files from the staging area, we use the following command:

```bash
git commit -m "Commit message"
```

Inside the quotes, we should write a **commit message** which is used to identify it in the commit history.

The commit message should be a descriptive summary of the changes that you are committing to the repository.

After executing that command, you will get the technical details about the commit printed in the terminal. And that's basically it, you have successfully made a commit in your project!

you can see Commit history on github.com

## Get Started with Git

1. Install Git from the [official website](https://git-scm.com/downloads).
1. If everything went well, it should return the Git version that is installed on your computer.
1. If you don't have already Sign up for an account at [github.com](https://github.com/signup).
1. Once inside, you'll find your own Repositories.
1. Create a new project or artwork by simply clicking the `New` button and giving it a unique name.
1. To initialize a local repository and start tracking your project, in terminal and navigate to the main folder of your project, then type `git init`. This command will generate a hidden `.git` folder in your project, where Git stores all internal tracking data for the current repository. We don't need to look and change in .git.
1. Keep your repos public and share your code with world.
1. Add your digital creations to the repository – your code, documents, images, or anything you create!

## Configure Git

Open Terminal and type the commands given below to configure it. Replace the values inside the quotes with your name and email address.

```bash
git config --global user.name "Your Name"
```

```bash
git config --global user.email "yourname@example.com"
```

GitHub recently changed the default branch on new repositories from master to main, change the default branch for Git using this command:

```bash
git config --global init.defaultBranch main
```

To verify things are working properly, enter these commands and verify that the output matches your name and email address:

```bash
git config --get user.name
```

```bash
git config --get user.email
```

YOU ARE READY TO GO!

### Basic Commands

To copy a github repo to your computer

```bash
git clone <link>
```

```bash
git add .
```

```bash
git commit -m "my message"
```

To send changes to your remote repository

```bash
git push origin main
```

If you have not cloned an existing repository and want to connect your repository to a remote server, you need to add it with

```bash
git remote add origin <link of your repo>
```

To update your local repository to the newest commit, execute

```bash
git pull
```

## [Ignoring files](https://help.github.com/en/articles/ignoring-files)

To ignore files or folders that you don't want to be tracked or added to the staging area, you can create a file called `.gitignore` in your main project folder. Inside of that file, you can list all the file and folder names that you definitely do not want to track


## Important Points to Remember

1. Repository is just a folder in Git.
1. Always make a repo before starting to code.
1. Keep committing code after finishing ever feature.
1. Keep you commit messages relevant to your feature.
1. Make a Pull Request after your work is done.

## Resources

|     |                                                                                                                                           |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| 1.  | [Complete Git Course (Basic to Advance) by Sir Zeeshan in Urdu](https://www.youtube.com/playlist?list=PLKueo-cldy_HjRnPUL4G3pWHS7FREAizF) |
| 2.  | [Git - the simple guide Article](https://rogerdudler.github.io/git-guide/)                                                                |
| 3.  | [GitHub Education's cheat sheet for commonly used git commands.](./git-cheatsheet.pdf)                                                    |
| 4.  | [Learn Basic Git Commands](https://www.youtube.com/watch?v=USjZcfj8yxE)                                                                   |
| 5.  | [Learn Basics of GitHub](https://www.youtube.com/watch?v=nhNq2kIvi9s)                                                                     |
| 6.  | [Fireship teaching Git in 12min](https://youtu.be/HkdAHXoRtos)                                                                            |

### What's Next?

After learning the basic commands, dive deep into the following:

1. Cloning a repo
1. Forking a repo
1. Difference between cloning and forking
1. Difference between origin and upstream
1. Branches
1. Merge Conflicts
1. Pull Requests

### Activity

Doing this small activity will give you a hands-on experience and help cement your knowledge:

1. Fork this very repo.
1. Clone it on your local machine.
1. Create a new branch <Your_Name>.
1. Edit README, add a new line and write, "<Your_Name>: I did it!".
1. Commit the changes to your local repo.
1. Push the code to your remote repo (the forked one).
1. Send a pull request to me so I can accept your changes in this original repo.

---

<h3 align="center">Show some ❤️ by <img src="https://imgur.com/o7ncZFp.jpg" height=25px width=25px> this repository</h3>
