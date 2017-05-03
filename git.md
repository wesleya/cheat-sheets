# Git Cheet Sheet

## Show Branches

shows both remote and local branches
```
git branch -a
```

shows remote branches.
```
git branch -r
```

shows local branches
```
git branch
```

## Checkout/Push Branches

checkout branch from remote
```
git checkout features/convert-idn-to-utf8-characters
```

checkout new branch
```
git checkout -b feature
```

push new branch to remote of same name
```
# push this branch to our central repository so it can be shared
# note the -u is to set up your local branch to track origin
git push -u origin feature
```

stage all removed files
```
git add -u
```

## File Changes

revert a modified file
```
git checkout {file}
```

revert file from another branch
```
git checkout <branch_name> -- <paths>
```

unstage a file, leaving it modified
```
git reset HEAD {file}
```

## Diffs

todo

## New Repo

Add existing brand new repo to gitlab:
first create your project

Existing folder or Git repository
```
cd existing_folder
git init
git remote add origin git@gitlab.com:wagena/frontend-dashboard-hackday.git
git add .
git commit
git push -u origin master
```