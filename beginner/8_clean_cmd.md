## command to clean untracked files and folders :

These commands will perform a dry-run showing which untracked files would be removed/ cleaned

```
git clean --dry-run
```
```
git clean -n
```

These commands will perform a dry-run showing which untracked files and folders would be removed/ cleaned

```
git clean -d --dry-run
```
```
git clean -dn
```

These commands will remove all the untracked files

```
git clean --force
```
```
git clean -f
```

These commands will remove all the untracked files and folders 

```
git clean -d --force
```
```
git clean -d -f
```
```
git clean -df
```

These commands will remove only ignored files

```
git clean -x --force
```
```
git clean -xf
```




