# Revisions and the Cloud

This entry summarizes the topics discussed during lecture, and information from [Git Tutorial: A Comprehensive Guide](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/#7_2).

## Local Repository Structure

The local Git repo has three components:

1. Working Directory (actual files reside here)
2. Index (area used for staging)
3. Head (points to the most recent commit)

## Getting Started

Before performing the following exercises, you must first ensure your computer is up to date and install the latest version of Git. Setup your computer by following these [instructions](https://codefellows.github.io/setup-guide/).

## Linking Repos

Repositories created on the GitHub website are stored in a cloud based system. You can connect your cloud repository to your local device by copying it and pasting it in your device’s terminal. When the repositories are connected, they can communicate with each other by sending and receiving code from the other repository. The following sections will outline how to connect your repos.

### Cloning Repos

The first step in connecting your repos is to clone the cloud repo. Within the GitHub repository dashboard, click the green button that says clone or download. Copy the HTTPS option to your clipboard. By cloning the repo, you have copied all versions of files for that project.

Next, open your terminal and use the cd and ls command to navigate to the projects directory. For this exercise, I did not have a projects folder, but there is a simple way to create a new folder.

* Go to your home directory: `cd ~`
* Make a folder to hold your repos: `mkdir projects`
* Rename it: `cd projects`
* Check where you are using Print Work Directory: `pwd`

### using git clone

* Within your new project directory, type: `git clone` + `space` then paste link and hit enter
* You just made a new folder that is stored locally and in sync with the one on GitHub! Take a look at it using the list command: ls
* Change into that directory: `> cd` + `space` + `file name`
* See the GitHub repo URL: `git remote -v`

### Using git status

* Before committing the repo, we need to review the current status: `> git status`
* The terminal will tell you what has changed since your last commit. If it says "nothing to commit, working directory clean," this means there are no files that have been tracked of modified.
* Open the current folder with VSCode: `> code .`
* Make changes, save and rerun `> git status`

### Using git add

Next, we will track all files in the repository and stage our file for the commit: `> git add` + `file name`

You can run `git status` once more to see information about the changes that are staged to commit.

### Using git commit

Almost there! Type `> git commit -m` + `“your message”`

What do these command mean? Let’s break it down a little further:

* `> git commit` takes a “snapshot” of your work
* `-m` specifies your message

To commit all changes, you can also type: `> git commit -a`

### Using git push

Type `> git push origin` to sync your local code to the repo stored on GitHub. Git will automatically give the name “origin” to the server from which you cloned and the name “master” to your local branch.

### Verify on GitHub

Just for safe measure, refresh your repo in your browser to ensure the repo synced to GitHub

## Stashing Changes

Alternatively, you may not want to commit your changes just yet, but you definitely do not want to lose them either. Use `git stash` to temporarily remove changes and hide them. When you are ready to continue working, use `git stash apply` to retrieve your hidden changes.

## Using git remote

Running the `git remote` command allows you to see all of the short names of the specified remote handles

Running `git remote -v` allows you to view the remote URLs next to the corresponding short names

## Help

There are three ways to access the manual for help or get more information on a particular command.

1. `git help <command>` or `git help <concept>`
2. `man git <command>`
3. `git <command> --help`
