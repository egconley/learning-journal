# Read 03: Revisions and the Cloud - Git and GitHub
Notes from [udemy Git Tutorial](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)

## What is git?
> Snapshots: Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.

## 3 states of files in git
- committed
- modified
- staged

## How to clone a repository from GitHub
1. In the GitHub repo, click on "Clone" and copy the url.
2. In the terminal: `git clone https://github.com/repo-name`

> By cloning the file, you have copied all versions of all files for a project.

## Workflow

### Local Repository Structure
The local Git repository has three components:
1. Working Directory: The actual files reside here.
2. Index: The area used for staging
3. Head: Points to the most recent commit

![workflow](https://blog.udemy.com/wp-content/uploads/2015/08/image036.png)

## Saving Changes

Tracked files: "can be modified, unmodified, or staged; they were part of the most recent file snapshot"
Untracked files: "were not in the last snapshot and do not currently reside in the staging area."

## Notes from class:
1. *in GitHub* Create new repo in GitHub
2. Clone to your local machine
  - *from terminal* `git clone <repo url from GitHub>`
3. Add stuff 
  - *from terminal* `code .`
  - make changes in VS code
  - save the changes in VS code
4. ACP (status)
  - *from the terminal* 
    - `git status`
    - `git add <filename>`
    - `git status`
    - `git commit -m "comment"`
    - `git status`
    - `git push origin master`
    - `git status`