# Commands I Find Useful

## Git-related

* Remove local branches that have been merged 

 ```
 git branch --merged | egrep -v "(^\*|master|main)" | xargs git branch -d
```

* Sorting local branches by last commit date

 ```
 git for-each-ref --sort=-committerdate refs/heads/ --format='%(committerdate:short) %(refname:short)'
```

## nginx

* Restart

```
nginx -s restart
```

## Misc Mac commands

* Dump environment variables to the screen

```
printenv
```
