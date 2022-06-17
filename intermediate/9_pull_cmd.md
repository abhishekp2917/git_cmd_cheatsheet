## command to pull (fetch and merge remote branch with tracking branch) remote branch :

These commands will pull the remote changes to loacl repo 

```
git pull <remote name> <remote branch name>
```
```
git pull <remote URL> <remote branch name>


These commands will pull the remote changes to loacl repo if current branch is set for tracking remote branch

```
git pull <remote name>
```
```
git pull <remote URL>
```
```
git pull
```

These commands will pull the remote changes and remove the deleted remote branch from local repo

```
git pull <remote name> --prune
```
```
git pull <remote URL> -p
```
```
git pull -p
```

