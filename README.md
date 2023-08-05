<h1 align="center">Git and GitHub</h1>

<p align="center">
<img src="https://skillicons.dev/icons?i=git,github" />
</p>

## Index

- [What is Git]()

### What is [Git](https://git-scm.com/)

Git is a [distributed](https://git-scm.com/about/distributed) version control system (VCS). In other words, it's a system that tracks changes to our project files over time. It enables us to record project changes and go back to a specific version of the tracked files, at any given point in time.  This system can be used by many people to efficiently work together and **collaborate on team projects**, where each developer can have their own version of the project, distributed on their computer. Later on, these individual versions of the project can be merged and adapted into the main version of the project.

Basically, it's a massively popular tool for coordinating parallel work and managing projects among individuals and teams. Needless to say, knowing how to use Git is one of the most important skills for any developer nowadays - and it's definitely a great addition to your resume!

### Get Started with Git

1. Install Git from the [official website](https://git-scm.com/downloads).
1. Create a GitHub account, if you don't have one already.

### Configure Git

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

## Precaution

1. Repository is just a folder in Git.
1. Always make a repo before starting to code.
1. Keep committing code after finishing ever feature.
1. Keep you commit messages relevant to your feature.
1. dfd

## Resources

|     |  |
| --- | ---------------------------- |
| 1.  | [Complete Git Course (Basic to Advance) by Sir Zeeshan in Urdu](https://www.youtube.com/playlist?list=PLKueo-cldy_HjRnPUL4G3pWHS7FREAizF) |
| 2.  | [Git - the simple guide Article](https://rogerdudler.github.io/git-guide/)                                                                |
| 3.  | [Learn Basic Git Commands](https://www.youtube.com/watch?v=USjZcfj8yxE)                                                                   |
| 4.  | [Learn Basics of GitHub](https://www.youtube.com/watch?v=nhNq2kIvi9s)                                                                     |

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

\
**Note:**
I have included GitHub Education's Git cheat sheet in the repo that contains some commonly used git commands. You can view it here: [git-cheatsheet.pdf](git-cheatsheet.pdf).

---

### If you find the repo useful, do support it by giving a star. ⭐

Author :
[![Follow codesnerd on GitHub](https://img.shields.io/badge/Connect-codesnerd-blue.svg?logo=Github&longCache=true&style=social&label=Follow)](https://github.com/codesnerd)
