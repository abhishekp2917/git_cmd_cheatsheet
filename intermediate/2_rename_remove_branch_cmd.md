## command to rename the branch :

These commands will rename current branch.

```
git branch --move <new branch name>
```
```
git branch -m <new branch name>
```

These commands will rename the branch specified in input.

```
git branch --move <old branch name> <new branch name>
```
```
git branch -m <old branch name> <new branch name>
```


_________________________________________________________________________________________________________________________________________



## command to remove/ delete the branch :

These commands will delete the branch specified in input. But the given branch must have merged with the branch from which its is originated.

```
git branch --delete <branch name>
```
```
git branch -d <branch name>
```

These commands will delete the branch specified in input irrespective of any conditions.

```
git branch --delete --force <branch name>
```
```
git branch -d --force <branch name>
```
```
git branch -df <branch name>
```
```
git branch -D <branch name>
```
