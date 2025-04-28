# + Git command +

# + Git setup

git --version : to check version of git
git config --global user.name '' : used to create username
git config --global user.email '' : used to connect our umail with username

# + Repository

## Repository is where git track everything in our project

## Repository is like a folder that store our project

git config --global initdefaultBranch main : change branch
git init : used to check initialize repository
git status : used to see files in our project commit or not
git add fileName : used to commit file for git to track
git add . : commit all file
git commit -m '' : used to note messages
git log : used to see all history message we committed
git checkout hashOrSpecificCommit : change HEAD to old or previous version of git
git checkout main : change HEAD to the lastest commit
git checkout -f main : if made some change and wanna go to the lastest commit
git branch -M main : change repository to main
git remote add origin repoGithubLink: link git to github
git push -u origin main :push local commit to github
git branch brachName : create new branch
git checkout branchName : to checkout or change branch
git checkout -b branchName : create branch to move to it immidaitely
git branch new-branchName source-branch : create a new branch to another specific branch
git push --set-upstream origin branchName OR git push -u origin branchName : publish local branch
git push : used when publish local branch already
git pull : pull other changes to our local

git remote show origin : show branch in our repo

# + Git Conflicts

git merge main : merge or pull main branch to our branch

# + reset

## soft reset

git reset --soft <commit-hash> : moved specified commit to history and keep changes stage to work directory and in stage

## mixed reset

git reset <commit-hash> : moved specified commit to history and keep changes stage to work directory but not in stage

## hard reset

git reset --hard <commit-hash> : discard specific commit

git stash apply stash_name : go back to uncommit that we stash

git stash list : check stash list
