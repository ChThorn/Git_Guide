How to use git
==============

First we have to run in termin of vscode as this:

`git init`

`git add .`

`git commit -am "feature signup working"`

### or 

`git commit -m "initial commit"`

### To remote to github repo:

`git remote add origin https://github.com/yourrepo`

`git push -u origin master`

## or 

`git push origin main`

***Check the git status at github***
`git checkout anothername`

### if not see any name, then using this:
`git checkout -b createnamebranch`

Also, to check status, we can use:
`git status`

--------------------
# Create a version

`git init`

`git status`

`git add .`

`git commit -m "Message"`

# View Previous Versions

`git log --all --graph`

`git checkout <commit_hash>`

`git checkout <branch_name>`

# Restore to Previous Versions
`git checkout <hash|branch> <file|folder>`

`git commit -m "Message"`
