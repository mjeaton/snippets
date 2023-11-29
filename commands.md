# Commands I Find Useful

## Git-related

Remove local branches that have been merged 

 `git branch --merged | egrep -v "(^\*|master|main)" | xargs git branch -d`
