
# Git 


Download & Install Git From: http://git-scm.com/downloads


### Configuring Git Settings (Intial Setup) 

`git config --global user.email "you@example.com"`

`git config --global user.name "your-name"`


### Checking Configuration

`git config user.name`

`git config user.email`


### Making Repos

`git init`

`git init <name>`

`git clone <url>`


### Making Changes

`git status`

`git add .`

`git add --all`

`git commit -m "Commit Message"`


### Adding Remote 

`git remote add origin https://github.com/user/repo.git`


### Checking Added Remote

`git remote -v`


### Pushing Repo Code

`git push -f`

`git push origin master `


### Removing Cached Files from the Git Staging 

`git rm -r --cached .`


### Fetching and Pull

`git fetch`

`git pull `


### Changing Commit Message

`git commit --amend -m "New commit message"`


### Remove or Undo Last Commit

`git reset --soft HEAD~1`

`git reset [commit]`


### Review History

`git log`

`git log --follow [file]`

`git show [commit]`


### Group Changes

`git branch`

`git checkout [branch-name]`

