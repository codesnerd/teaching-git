Assuming you all are using Windows 10.

# Get Started

1. Install Git from the [official website](https://git-scm.com/downloads).
2. Create a GitHub account, if you don't have one already.

# Configure Git

Open Terminal (or Git Bash if you're on Windows) and type the commands given below to configure it. Enter your information inside the quotation marks.

```
git config --global user.name "Your Name"
```

```
git config --global user.email "your_email@example.com"
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

### To [generate a new SSH key](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent):

1. Open Terminal.
2. Run the following command, replacing the email with your GitHub email address.

```
ssh-keygen -t ed25519 -C "your_email@example.com"
```

When prompted to "Enter a file in which to save the key", you can press Enter to accept the default file location (which is`~/.ssh/`).

3. At the prompt, type a secure passphrase (you can press Enter for no passphrase). For more information, see [Working with SSH key passphrases](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/working-with-ssh-key-passphrases).

> Enter passphrase (empty for no passphrase): [Type a passphrase]\
> Enter same passphrase again: [Type passphrase again]

### To [add SSH key to your GitHub account](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account):

1. Copy the SSH public key to your clipboard.

```
pbcopy < ~/.ssh/id_ed25519.pub
```

This copies the contents of the `id_ed25519.pub` file to your clipboard. Make sure the filename you specify in the command matches your SSH public key filename.

2. On GitHub, click your profile picture in the upper-right corner, then click Settings.
3. In the "Access" section of the sidebar, click SSH and GPG keys.
4. Click New SSH key.
5. In the "Title" field, add a descriptive label for the new key. For example, if you're using a personal laptop, you might call this key "Personal laptop".
6. Select the type as "Authentication Key".
7. In the "Key" field, paste your public key.
8. Click Add SSH key.
9. If prompted, confirm access to your account on GitHub.

### To [test your SSH connection](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh/testing-your-ssh-connection):

1. Open Terminal.
2. Run the command:

```
ssh -T git@github.com
```

You may see a warning like this:

> The authenticity of host 'github.com (IP ADDRESS)' can't be established.\
> ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.\
> Are you sure you want to continue connecting (yes/no)?

3. Verify that the fingerprint in the message you see matches [GitHub's public key fingerprint](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/githubs-ssh-key-fingerprints). If it does, then type yes:

> Hi USERNAME! You've successfully authenticated, but GitHub does not
> provide shell access.

4. Verify that the resulting message contains your username.

#### 🎉 VOILA! YOU ARE READY TO GO!

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
7. Pull Requests

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

### If you find the repo useful, do support it by giving a star. ⭐

## 🖋 Author

Follow my GitHub profile to stay updated with my latest projects:

[![Follow codesnerd on GitHub](https://img.shields.io/badge/Connect-codesnerd-blue.svg?logo=Github&longCache=true&style=social&label=Follow)](https://github.com/codesnerd)

## 👍 Acknowledgements

- Videos and Notion notes by [Colt Steele](https://www.youtube.com/c/ColtSteeleCode)
