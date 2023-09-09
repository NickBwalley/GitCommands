# GitHub CheatSheet

## Basic GitHub Commands

To perform a github clone

```
git clone https://github.com/username/repo_name.git
```

Assume you have a project `gitty-project` you would like to add to github. Here are the steps

Initialize a git repo

```
git init
```

Add all files to the git staging area

```
git remote add origin https://github.com/username/gitty-project.git
```

```
git add .
```

Confirm that it has been added to the git staging area

```
git status
```

Commit your changes witth a message `initial commit`

```
git commit -m "initial commit"
```

Push your changes to `main` github repo `gitty-project`

```
git push -u origin master
```

## Working with GitHub Branches

creates a github branch

```
git branch [branchname]
```

creates a branch and switches to that branch immediately

```
git checkout -b [branchname]
```

List github branches

```
git branch -a
```

Delete a branch

```
git branch -d [branchname]
```

Rename a local branch

```
git branch -m [old branch name] [new branch name]
```

Switch to a branch

```
git checkout [branchname]
```

## Advanced GitCommands

Remove a file from the Git Staging area

```
git rm --cached [filename]
```

Adds any file with a `.html` extension

```
git add *.html
```

Configure git staging and pushing to your GitHub account

```
git config --global user.name [your_github_username]
git config --global user.email [your_email]
```

CLONE WITHIN AN ORGANIZATION ---------------
$ git clone https://username@github.com/org_name/repo_name.git

# GIT COMMANDS

---

###### install package_name.deb command

$ sudo dpkg -i package_name.deb
