## How to revert/ undo the changes of certain commit :

### first method :


- Run below command to undo the changes of given commit and add it to staging index.

This command will undo chnages of all the files 

```
git checkout <SHA value/ tag/ branch/ HEAD/ anccestry> .
```

This command will undo chnages of specified file 

```
git checkout <SHA value/ tag/ branch/ HEAD/ anccestry> <file name>
```

- Commit the staged files along with apprepriate commit message.

```
git commit -m '<commit message>'
```

### second and easy method :

- Run below command to undo the changes of given commit and add will open editor to enter commit message to commit

This command will undo chnages of all the files 

```
git revert <SHA value/ tag/ branch/ HEAD/ anccestry> .
```

This command will undo chnages of specified file 

```
git revert <SHA value/ tag/ branch/ HEAD/ anccestry> <file name>
```


