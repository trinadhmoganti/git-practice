# `git` useful commands

## Squash commits locally
`git rebase -i HEAD~3` // 3 is number of commits to display

## Update timestamp for last commit
`git commit --amend --date="now"`

## Force on a particular branch
`git push origin +<branch-name>` // observe the `+` sign

## Delete most recent commit locally
`git reset --hard HEAD~1` // deletes last commit and work done too

`git reset --soft HEAD~1` // deletes last commit but preserves your work
