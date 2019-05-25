# git-play [![Build Status](https://travis-ci.org/lawrenceogri/git-play.svg?branch=master)](https://travis-ci.org/lawrenceogri/git-play)
This is a repo to practice git commands, learn markdown and add badges!

## Getting Started

### Initialize
`git init` Initialize a local repository

### Commit

`git add [File Name]` Add file to staging index

#### Add Suffixes

`git add .` Adds all file/folders in directory to staging index

`git commit -m "[Commit Message]"` Commit staged files

### Log
`git log`


#### Log Suffixes
`-n` Limit number of commits shown

`--since/until-YYYY-MM-DD` Sift log by date 

`--author="authorName"` Search log by author name

`--grep="Expression"` Search commit message for messages matching expression




## Making Changes

### Status
`git status` Difference between working directory, staging index and repository

### Differences
`git diff` Compares what's in the repository with what's in the working directory

### Diff Suffixes
`--staged` Reports changes in the staging index and the repository

### Delete Files
`git rm [File Name]` Afterward, commit changes(deletions) with `git commit`

### Renaming/Moving Files
`git add [New File Name]`

`git rm [Old File Name]`

or in one step...
`git mv [Old File Name] [Folder Dir/New File Name]`



## Undo Changes

### Checkout
`git checkout` 

`git checkout -- [file name]` Don't checkout a branch, check out a file on this directory

### Unstage
`git reset HEAD [File Name]`

### Ammending Commit
`git commit ammend -m "Commit message"`

