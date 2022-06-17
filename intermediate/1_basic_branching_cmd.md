## command to create branch :

This command will create branch with given branch name from the current HEAD location.

```
git branch <branch name>
```

This command will create branch with given branch name from the reference commit.

```
git branch <branch name> <SHA value/ HEAD/ other branch name/ tag name/ ancestry>
```

____________________________________________________________________________________________________________________________________________


## command to view the branches :

These commands will list all the local branches and will highlight current branch with '\*' before the branch name.

```
git branch
```
```
git branch --list
```
```
git branch -l
```

These commands will list all the remote branches.

```
git branch --remote
```
```
git branch -r
```
```
git branch --list  --remote
```
```
git branch -l -r
```
```
git branch -lr
```

These commands will list all the branches both local and remote and will highlight current branch with '\*' before the branch name.

```
git branch --all
```
```
git branch -a
```

____________________________________________________________________________________________________________________________________________


## command to view the merged and unmerged branches :

These commands will show all the branches which are merged with current branch.

```
git branch --merged
```
```
git branch --list --merged
```
```
git branch -l --merged
```

These commands will show all the branches which are not merged with current branch.

```
git branch --no-merged
```
```
git branch --list --no-merged
```
```
git branch -l --no-merged
```

____________________________________________________________________________________________________________________________________________


## command to switch to other branch :

This command will switch to the branch specified in input and set the HEAD pointer to the tip of that branch.

```
git switch <branch name>
```

This command will create and switch to the branch specified in input and set the HEAD pointer to the tip of that branch.

```
git switch -c <branch name>
```


