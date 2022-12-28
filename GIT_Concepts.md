## Git 
Version Control Tool/Software, allows you to save checkpoints of your code changes and have different versions of your code

## GitHub / GitLab
Service that uses git to store projects on the cloud and allows you to collaborate with others

## General Concepts / Terminology
- `Repository` - The project that git is configured with
  - **Local** Repository - On your computer
  - **Remote** Repository - On the cloud (github)
- `Commit` - a checkpoints of saved code changes
- Branch - TBD


## How to use Git
- `git` needs to be installed on your machine (windows, mac, linux, etc...)
- To check if git is installed run the command `git --version`, if something shows up then git is installed
- To check if a project is a git repository, run `git status`
- To initialize a project as a repository run `git init`

## How to check if a project (folder) is a git repository
1. Navigate to the location of your project
2. Run:
    ```commandline
     git status
    ```
3. If you get this message (then it is not a git repository):
    >  fatal: not a git repository (or any of the parent directories): .git

## Git Commands
- Create new git repository in your current location
  ```commandline
  git init
  ```
- Check repository status
  ```commandline
  git status
  ```
- Add files to staging area
  ```commandline
  git add <file-name>
  ```
- Capture a snapshot of the staging area (committing)
  ```commandline
  git commit -m "<commit-message>"
  ```
- See commit history
  ```commandline
  git log
  git log --oneline
  ```
- Remove files or folders from staged area
    ```commandline
    git restore --staged <file-name>
    ```
- Reset to an older commit
  ```commandline
  git reset <commit-id>
  git reset --hard <commit-id>
  ```
