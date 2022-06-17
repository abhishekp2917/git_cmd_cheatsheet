## command to save/ stash changes :

This command will stash the uncommited changes (all tracked changes in staging index as well as working directory)

```
git stash
```

Run below command to stash changes and give a message to stashed data

```
git stash save '<stash message>'
```

This command will stash untracked files as well

```
git stash --include-untracked --message  '<stash message>'
```
```
git stash -u -m '<stash message>'
```
```
git stash -um '<stash message>'
```

____________________________________________________________________________________________________________________________________________


## command to view stash :

This command will list all the stash irrespective of which branch HEAD is pointing to

```
git stash list
```

____________________________________________________________________________________________________________________________________________


## command to apply stash changes to current working directory :

This command will apply top stash to current working directory

```
git stash apply
```

Run below command to apply stash based on stash number 'n'

```
git stash apply stash@{n}
```
```
git stash apply n
```

____________________________________________________________________________________________________________________________________________


## command to apply stash and remove it from the list

This command will apply top stash to current working directory and remove it from the list

```
git stash pop
```

Run below command to apply stash based on stash number 'n' and remove it from the list

```
git stash pop stash@{n}
```
```
git stash pop n
```

____________________________________________________________________________________________________________________________________________


## command to remove stash from the list

This command will remove top stash from the list

```
git stash drop
```

Run below command to remove stash based on stash number 'n' from the list

```
git stash drop stash@{n}
```
```
git stash drop n
```
























































