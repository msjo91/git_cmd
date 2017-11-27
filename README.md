# Git Basic Commands
Ignore <>
### Help
command | task
--- | ---
git | View help
git \<cmd> --help | View specific help for a command
### Create
command | task
--- | ---
git init | Create a new local repository
git clone username@host:/path/to/repository | Copy a remote repository
### Configure
command | task
--- | ---
git config --global user.name "\<name>" | Configure author name to be used with commits
git config --global user.email \<email> | Configure email address to be used with commits
### Local
command | task
--- | ---
git status | View staging
git add \<file> | Add a file to staging
git add -A | Add all files to staging
git commit -m "\<msg>" | Commit with commit message
git diff | View merge conflicts
git log | View commit logs
### Remote
command | task
--- | ---
git remote -v | List all currently configured remote repositories
git remote add origin \<server> | Connect to a remote repository naming 'origin'
git push -u origin master | Push commits to remote repository with upstream (tracking reference)
git pull | Fetch and merge changes on remote server to working directory (need .git)
### Branch
command | task
--- | ---
git branch -a | List all local and remote branches
git branch \<branch> | Create a brach
git checkout \<branch> | Switch to branch
git branch -d \<branch> | Delete branch
git push origin \<branch> | Push branch to remote repository
git push origin :\<branch> | Delete a branch on remote repository
git merge \<branch> | Merge a branch into currently active branch
