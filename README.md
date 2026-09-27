# learn-git
Learn git from the beginning

## Test section

Hello world!


## check status

`git status`


## stage changes

`git add file1 file2 ....`

Example: 

`git add README.md`

## commit changes

`git commit -m "your message"`

Example:

`git commit -m "Test commit"`

## push changes into remotes

`git push`

push a new branch in local:

`git push --set-upstream origin test-branch` to push a `test-branch` into git 

## create a new branch

`git checkout -b your-new-branch`

Example:

`git checkout -b test-branch` will create a new branch with name `test-branch` from the main branch

## checkout a branch 

`git checkout your-branch` to switch to `your-branch` locally

## logs 

`git log` to show the commit history 


## fetch new changes from git 

`git fetch` to fetch new changes from git

## pull new changes from the current branch from git 

`git pull`

## git flows 

1. create a new branch

- indicate base branch (main for example)
- checkout base branch
- fetch origin changes from git
- pull new changes for the current base branch
- create a new branch from the base branch
- make changes
- stage changes
- commit changes
- push changes
- create a pull request
- (optional) update to align with the base branch
- review changes from the pull request
- resolve review comments 
- get review approvals
- merge the current pull request