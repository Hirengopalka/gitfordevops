# Git Commands Cheat Sheet

## Configuration

- Set User Information:
  git config --global user.name "Your Name"
  git config --global user.email "your.email@example.com"
  Sets your name and email for all Git commits.

## Repository Initialization

- Create a New Repository:
  git init
  Initializes a new Git repository in the current directory.

- Clone a Repository:
  git clone <repository_url>
  Clones an existing repository from the specified URL.

## Branching and Merging

- List Branches:
  git branch
  Lists all local branches.

- Create a New Branch:
  git branch <branch_name>
  Creates a new branch with the specified name.

- Switch to a Branch:
  git checkout <branch_name>
  Switches to the specified branch.

- Create and Switch to a New Branch:
  git checkout -b <new_branch_name>
  Creates a new branch and switches to it.

- Merge Branches:
  git merge <branch_name>
  Merges the specified branch into the current branch.

## Staging and Committing

- Check Status:
  git status
  Displays the status of your working directory and staging area.

- Add Changes to Staging Area:
  git add <file_name>
  Stages the specified file for commit.

- Commit Changes:
  git commit -m "Commit message"
  Commits the staged changes with a message.

- Amend the Last Commit:
  git commit --amend
  Amends the last commit with the current staged changes.

## Viewing History

- View Commit History:
  git log
  Shows a list of past commits.

- View Commit History with Diff:
  git log -p
  Shows commits along with the changes made in each.

## Undoing Changes

- Unstage a Staged File:
  git reset <file_name>
  Removes the specified file from the staging area.

- Revert a Commit:
  git revert <commit_hash>
  Creates a new commit that undoes the changes made by the specified commit.

- Reset to a Specific Commit:
  git reset --hard <commit_hash>
  Resets the repository to the specified commit, discarding all changes after it.

## Working with Remote Repositories

- Add a Remote Repository:
  git remote add <remote_name> <remote_url>
  Adds a new remote repository with the given name and URL.

- View Remote Repositories:
  git remote -v
  Lists all configured remotes with their URLs.

- Push Changes to Remote:
  git push <remote_name> <branch_name>
  Pushes the specified branch to the remote repository.

- Pull Changes from Remote:
  git pull <remote_name> <branch_name>
  Pulls the specified branch from the remote repository and merges it into the current branch.

## Tagging

- Create a Tag:
  git tag <tag_name>
  Creates a tag with the specified name at the current commit.

- Push Tags to Remote:
  git push --tags
  Pushes all local tags to the remote repository.
