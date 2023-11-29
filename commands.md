# Commands I Find Useful

Remove local branches that have been merged 

 `git branch --merged | egrep -v "(^\*|master|main)" | xargs git branch -d` 
