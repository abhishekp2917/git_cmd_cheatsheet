## command to see/ log all the past commits:


This command will log all the past commits along with meta data such as username, useremail, date, time, commit message, commit 'SHA' ID etc.

```
git log
```

__________________________________________________________________________________________________________________________________________


## log options :

- --online :

This command will log all the past commits in one single line with shorten SHA value (commit id).

```
git log --oneline
```

- --all/ -a :

This command will log all the past commits of all the branches of current respo.

```
git log --all
```
```
git log -a
```

- --author :

This command will log all the past commits whose author/ username contains the input substring.

```
git log --author='<username substring>'
```

- --grep :

This command will log all the past commits whose commit message contains the input substring.

```
git log --grep='<commit message substring>'
```

- --since :

This command will log all the past commits dated from the specified date in input

```
git log --since=<YYYY-MM-DD>
```

- --until :

This command will log all the past commits till the dated specified in input.

```
git log --until=<YYYY-MM-DD>
```

- --graph :

This command will log all the past commits in form of a graph.

```
git log --graph
```

- --decorate :

This command will log all the past commits in decorated fashion.

```
git log --decorate
```

- --format :

This command will log all the past commits in format specified in input.

```
git log --format=oneline
```
```
git log --format=short
```
```
git log --format=medium
```
```
git log --format=full
```
```
git log --format=fuller
```

__________________________________________________________________________________________________________________________________________


## command to log commit based on <tree-ish>(file name, SHA value, branch name, tag name, HEAD, HEAD accenstry) :

This command will show all commits which has given file name in it.
  
```
git log <file name>
```
  
This command will show all commits which belongs to given branch name.
  
```
git log <branch name>
```

This command will show all commits starting from given commit SHA value.
  
```
git log <SHA value>
```
  
This command will show all commits starting from given commit tag name.

```
git log <tag name>
```
  
This command will show all commits starting from the commit to which HEAD is pointing.

```
git log HEAD
```

This command will show all commits starting from the nth parent commit to which HEAD is pointing.
  
```
git log HEAD~<n>
```
 
This command will show all commits starting from the nth parent commit to which HEAD is pointing where 'n' is determine by number of '^'.  

```
git log HEAD^^^
```



































