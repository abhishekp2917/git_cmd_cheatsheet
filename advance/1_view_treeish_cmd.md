## command to view directory at different tree-ish :

This command will show all the blob (file) and tree (folder) at given commit reference

```
git ls-tree <SHA value/ branch name/ HEAD/ tag name/ ancestry>
```

## options for command 'ls-tree' :

- -d 

This command will show only tree (folder) at given commit reference

```
git ls-tree -d <SHA value/ branch name/ HEAD/ tag name/ ancestry>
```

- -r

This command will show all the files present in the repo by recursively traversing to the leaf level og the tree (folder)

```
git ls-tree -r <SHA value/ branch name/ HEAD/ tag name/ ancestry>
```

- --name-only

This command will show only the name of file and folder

```
git ls-tree --name-only <SHA value/ branch name/ HEAD/ tag name/ ancestry>
```

