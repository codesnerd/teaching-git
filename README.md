Assuming you all are using Windows 10.

# Get Started

1. Install Git from the [official website](https://git-scm.com/downloads).
2. Create a GitHub account, if you don't have one already.

# Configure Git

Open Git Bash and type the commands given below to configure it. Enter your information inside the quotation marks.
```
git config --global user.name "Your Name"
```
```
git config --global user.email "yourname@example.com"
```

GitHub recently changed the default branch on new repositories from master to main, change the default branch for Git using this command:

```
git config --global init.defaultBranch main
```

To verify things are working properly, enter these commands and verify that the output matches your name and email address:

```
git config --get user.name
```
```
git config --get user.email
```

# Generate and Add SSH Keys to GitHub

1. Generate SSH Keys: [GitHub Docs](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
2. Add SSH Keys to GitHub: [GitHub Docs](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)
3. Test Your SSH connection: [GitHub Docs](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh/testing-your-ssh-connection)

#### VOILA! YOU ARE READY TO GO!

# Learn Basic Git Commands

Video: [Learn Git In 15 Minutes](https://www.youtube.com/watch?v=USjZcfj8yxE)<br />
Notes: [Notion Notes](https://www.notion.so/zarkom/Introduction-to-Git-ac396a0697704709a12b6a0e545db049)


# Learn Basics of GitHub

Video: [Learn GitHub in 20 Minutes](https://www.youtube.com/watch?v=nhNq2kIvi9s)<br />
Notes: [Notion Notes](https://www.notion.so/zarkom/Introduction-to-GitHub-202af6f64bbd4299b15f238dcd09d2a7)

# What's Next?

After learning the basic commands, dive deep into the following:

1. Cloning a repo
2. Forking a repo 
3. Difference between cloning and forking
4. Difference between origin and upstream
5. Branches
6. Merge Conflicts
7. Pull Requests (Although we will work as collaborators instead of contributors but PR is an important concept to learn.)

# Activity

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

### If you found the repo useful, do support it by giving a star. ⭐
## 🖋 Author
Follow my GitHub profile to stay updated with my latest projects:

[![Follow codesnerd on GitHub](https://img.shields.io/badge/Connect-codesnerd-blue.svg?logo=Github&longCache=true&style=social&label=Follow)](https://github.com/codesnerd)

## 👍 Acknowledgements
* Videos and notes by [Colt Steele](https://www.youtube.com/c/ColtSteeleCode)
