## command to fetch changes from remote repository :

These commands will fetch any changes in the remote repository into local working directory

```
git fetch <remote name>
```
```
git fetch <remote URL>
```

These command will fetch changes only if the tracking branch is setup

```
git fetch
```

Run below commands to fetch any changes and remove remote branch from local repo it that branch has deleted from remote repo

```
git fetch --prune
```
```
git fetch -p
```
