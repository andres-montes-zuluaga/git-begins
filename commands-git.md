GIT COMMANDS

CLONE
To clone a repository:
git clone [link] && cd [repository-name]

PUSH
The three push commands, is necessary are in a main branch:
git add [add an file]
git add . [add all the files]
git commit -m "Add your comments"
git push [repository name] [branch name] 

PULL
General format:
git pull [options: --quiet, verbose, etc] [Repository URL] 
For specifyc branch:
git pull [Repository name] [Branch name]

BRANCH
Adding a new branch:
git branch [New-branch-name]
For moving us at the new branch:
git checkout [New-branch-name]
Shortcut, create and moving at the new branch:
git checkout -b [New-branch-name]