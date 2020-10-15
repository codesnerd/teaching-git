Assuming you all are using Windows 10.

# Get Started

1. Install Git: https://git-scm.com/downloads.
2. Create a GitHub account, if you don't have one already.

# Configure Git

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
