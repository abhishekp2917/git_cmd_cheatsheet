## command to push local commits to remote repository :

This command will push all the commits of given branch to remote repo

```
git push <remote name> <branch name>
```

These commands will push all the commits of given branch to remote repo and will set a tracking branch for the remote branch 

```
git push --set-upstream <remote name> <branch name>
```
```
git push -u <remote name> <branch name>
```

Run below command to push changes of current branch to remote repo if upstream is set for tracking remote branch by current branch

```
git push 
```

## command to set and unset upstream for tracking remote branch :

These commands will set the upstream for tracking remote branch

```
git branch --set-upstream-to <remote name>/<remote branch name> <tracking branch name>
```
```
git branch -u <remote name>/<remote branch name> <tracking branch name>
```

This command will unset the upstream for tracking remote branch

```
git branch --unset-upstream <tracking branch name>
```












