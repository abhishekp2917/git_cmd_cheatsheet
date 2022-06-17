## command to fetch changes from remote repository :

These commands will fetch any changes in the remote repository into local working directory

```
git fetch <remote name>
```
```
git fetch <remote URL>
```
```
git fetch
```

Run below commands to fetch any changes and remove deleted remote branch from local repo

```
git fetch <remote name> --prune
```
```
git fetch <remote URL> -p
```
```
git fetch --prune
```
```
git fetch -p
```

Run below commands to set configuration for fetch with prune option enable

```
git config fetch.prune true
```

