# Git and Git Basic Command

## Basic Git Command

**Git Config**
This command is used to set up your Git configuration, such as your name and email.

*Example:*
```bash
$ git config --global user.name "Your Name"
$ git config --global user.email "your@email.com"
```

**Git Init**
This command initializes a new Git repository in your current directory.

*Example:*
```bash
$ git init
```

**Git Clone**
To copy a repository from a URL to your local machine, you use this command.

*Example:*
```bash
$ git clone <repository_URL>
```

**Git Add**
To stage changes and prepare them for a commit, you use this command.

*Example:*
```bash
$ git add file.txt
```

**Git Commit**
After staging changes, you commit them to the repository along with a message.

*Example:*
```bash
$ git commit -m "Add new feature"
```

**Git Status**
This command shows the current status of your repository, including tracked and untracked files.

*Example:*
```bash
$ git status
```

**Git Push**
To send your committed changes from your local repository to a remote repository, you use this command.

*Example:*
```bash
$ git push origin master
```

**Git Pull**
To fetch changes from a remote repository and merge them into your local branch, you use this command.

*Example:*
```bash
$ git pull origin master
```

**Git Branch**
To list all the branches in your repository or create a new branch, you use this command.

*Example:*
```bash
$ git branch
$ git branch new-feature
```

**Git Merge**
To combine changes from one branch into another, you use this command.

*Example:*
```bash
$ git merge new-feature
```

**Git Log**
This command displays the commit history of your repository.

*Example:*
```bash
$ git log
```

These are some of the basic Git commands to get you started with version control in your projects.