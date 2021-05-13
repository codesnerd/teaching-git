Assuming you all are using Windows 10.

# Get Started

1. Install Git: https://git-scm.com/downloads.
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

1. Generate SSH Keys: https://bit.ly/377fWec
2. Add SSH Keys to GitHub: https://bit.ly/2Inqb3s
3. Test Your SSH connection: https://bit.ly/2STWp8D

#### VOILA! YOU ARE READY TO GO!

# Learn Basic Git Commands

Video: https://bit.ly/33YxJCk<br />
Notes: https://bit.ly/3w5fWFt


# Learn Basics of GitHub

Video: https://bit.ly/3iSDllK<br />
Notes: https://bit.ly/3dtmqVM

# What's Next?

After learning the basic commands, dive deep into the following:

1. Cloning a repo
2. Forking a repo 
3. Difference between cloning and forking
4. Branches
5. Merge Conflicts
6. Pull Requests (Although we will work as collaborators instead of contributors but PR is an important concept to learn.)

# Activity

Doing this small activity will give you a hands-on experience and help cement your knowledge:

1. Fork this very repo.
2. Clone it on your local machine.
3. Edit README, add a new line and write, "<Your_Name>: I did it!".
4. Commit the changes to your local repo.
5. Push the code to your remote repo (the forked one).
6. Send a pull request to me so I can accept your changes in this original repo.

---
**Note:**
I have included GitHub Education's Git cheat sheet in the repo that contains some commonly used git commands. View it here: [git-cheatsheet.pdf](git-cheatsheet.pdf)
