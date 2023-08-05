<h1 align="center">Git and GitHub</h1>

<p align="center">
<img src="https://skillicons.dev/icons?i=git,github" />
</p>

## Index

- [What is Git]()
- [What is a Repository]()

## What is [Git](https://git-scm.com/)

Git is a [distributed](https://git-scm.com/about/distributed) version control system (VCS). In other words, it's a system that tracks changes to our project files over time. It enables us to record project changes and go back to a specific version of the tracked files, at any given point in time. This system can be used by many people to efficiently work together and **collaborate on team projects**, where each developer can have their own version of the project, distributed on their computer. Later on, these individual versions of the project can be merged and adapted into the main version of the project.

Basically, it's a massively popular tool for coordinating parallel work and managing projects among individuals and teams. Needless to say, knowing how to use Git is one of the most important skills for any developer nowadays - and it's definitely a great addition to your resume!

### Features of git

1. **Safekeeping:** The Repository ensures the safety of your creations, acting like a powerful shield that protects your important treasures.

2. **Version Control:** Git keeps a record of every change you make to your project,so it has the ability to remember every change you make to your creations. It's like time-travel! So,if you make a mistake you can easily go back to a previous version if you need to.

3. **Sharing with Friends:** Invite your friends into the Repository, and they can marvel at your creations, give suggestions, or even add their own touches to your works.

4. **Collaboration:** . Multiple people can work together on the same project simultaneously, and Git helps merge everyone's work seamlessly.
The Repository makes it effortless for everyone to contribute their parts and merge them seamlessly.

5. **Backup:** Like a powerful shield, Git Repository protects your work from getting lost or damaged. Even if your computer misbehaves, your projects are securely stored and can be accessed from another computer.


### What is a Repository

Imagine a repository as a special place that stores all your creative projects, just like a treasure chest for your computer code and files. In the digital realm, a Git repository is a magical box that keeps track of every change you make to your code and files over time.

The Repository is like your personal storage area in the digital world. It helps you keep track of your school projects, artworks, or any other digital wonders you create. Instead of saving your work scattered all over your computer, you place everything inside this repository.

## Commit

commit is like page in history book that has its own unique id and can never be changed

`git add` will stage the files that will be part of my commit

takes a snapshot of current code
tip: make small commits

### What is CLI Tools

Git is primarily used via the command-line interface, which we can access with our system terminals.

## Get Started with Git

1. Install Git from the [official website](https://git-scm.com/downloads).
1. If you don't have already Sign up for an account at [github.com](https://github.com/signup).
1. Once inside, you'll find your own Repository
1. Create a new project or artwork by simply clicking the `New` button and giving it a unique name.
1. publc share with world
1. Add your digital creations to the repository – your code, documents, images, or anything you create!


## Configure Git

Open Git Bash and type the commands given below to configure it. Enter your information inside the quotation marks.

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

```bash
git clone <link>
```

(one time only)

```bash
git add .
```

```bash
git commit -m "my message"
```

```bash
git push
```

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

### What's Next?

After learning the basic commands, dive deep into the following:

1. Cloning a repo
2. Forking a repo
3. Difference between cloning and forking
4. Difference between origin and upstream
5. Branches
6. Merge Conflicts
7. Pull Requests (Although we will work as collaborators instead of contributors but PR is an important concept to learn.)

### Activity

Doing this small activity will give you a hands-on experience and help cement your knowledge:

1. Fork this very repo.
2. Clone it on your local machine.
3. Create a new branch <Your_Name>.
4. Edit README, add a new line and write, "<Your_Name>: I did it!".
5. Commit the changes to your local repo.
6. Push the code to your remote repo (the forked one).
7. Send a pull request to me so I can accept your changes in this original repo.

---

### If you find the repo useful, do support it by giving a star. ⭐

Author :
[![Follow codesnerd on GitHub](https://img.shields.io/badge/Connect-codesnerd-blue.svg?logo=Github&longCache=true&style=social&label=Follow)](https://github.com/codesnerd)
