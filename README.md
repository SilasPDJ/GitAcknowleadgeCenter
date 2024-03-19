# UseFul Commands in GIT BASH

## useful linux commands in git bash

- `pwd`
- `code <filename>` also creates the file if not exists yet
- `source activate`
- `echo $VIRTUAL_ENV`
- `deativate`

## useful commands in git

### **Always read the tips in git console**

- ### `git status`
- `git add <filename>`
- `git commit -am`
- `git checkout -- <filename>`: remove changes in file
- `git commit --amend`

## reflog

`git reflog HEAD@{2.days.ago}`
`git reflog HEAD@10`
`git checkout HEAD@3`

#### Remove unreachable commits:

- `git reflog expire --expire-unreachable=now --all`
- `git gc --prune=now`

### Squash

- `git push -u origin SquashingBranch`
- `git fetch origin --prune` : After squashing / merging in repository

## stagging area (switch branches)

- `git stash`
- `git checkout -b newbranch`
- `git stash pop`

## Authentication new way:

- https://github.com/settings/ -> Developer Settings -> Personal access tokens
