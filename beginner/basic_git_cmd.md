## command to initialize git repo :

This will initialize or convert current directory into git repo and will add '.git' folder inside current repo

```
git init
```

run any of the below commands to check if '.git' folder is present or not

```
ls -a
```
```
ls -l -a
```
```
ls -la
```

_________________________________________________________________________________________________________________________________________


## command to check status of current repo :

This will show info about current repo like what are the files which is untracked/ modified/ deleted/ staged etc.
Moreover, it also give info about any merge conflicts if arised.

```
git status
```

_________________________________________________________________________________________________________________________________________


## command to add file/ files into staging index from working directory : 

This will add specific file present in working directory into staging index

```
git add <filename.extension>
```

This will add all the files present in working directory into staging index

```
git add .
```

_________________________________________________________________________________________________________________________________________


## command to add commit : 

### Below commands will commit all the files present in staging index. It is mandatory to provide commit message for each commit.
It could be a single line or multi-line commit.

This command is for giving single-line message in git bash itself

```
git commit -m "<commit message>"
```

This command is for giving single-line/ multi-line message as it will open default editor which was set in config file earlier.

```
git commit
```

### Below commands will commit all the files present in staging index as well as working directory

These commands are for giving single-line message in git bash itself

```
git commit --all -m "<commit message>"
```
```
git commit -a -m "<commit message>"
```
```
git commit -am "<commit message>"
```

These commands are for giving single-line/ multi-line message as it will open default editor which was set in config file earlier.

```
git commit --all
```
```
git commit -a
```

_________________________________________________________________________________________________________________________________________


## command to see difference between two <tree-ish> :
  
### command to see diff between working directory and previous commit of current branch
  
This command will differentiate between all the files of working directory with previous commit.

```
git diff  
```
```
git diff .  
```
  
This command will differentiate between working directory file with previous commit file specified in input.

```
git diff <file name>
```
  
  
  
### command to see diff between staged and previous commit of current branch
  
This command will differentiate between all the files of staging index with previous commit.

```
git diff --staged
```
```
git diff --staged .  
```
  
This command will differentiate between staging index file with previous commit file specified in input.

```
git diff --staged <file name>
```
  
  
  
### command to see diff between two commits
  
This command will differentiate between all the files of two commits specified in input.

```
git diff <SHA value of 1st commit> <SHA value of 2nd commit>
```
```
git diff HEAD~n1 HEAD~n2
```
```
git diff HEAD^^ HEAD^^^
```
  
This command will differentiate between file two commits specified in input.

```
git diff <SHA value of 1st commit> <SHA value of 2nd commit> <file name>
```
```
git diff HEAD~n1 HEAD~n2 <file name>
```
```
git diff HEAD^^ HEAD^^^ <file name>
```

  
  
  
### command to see diff between two tags
  
This command will differentiate between all the files of two tags specified in input.

```
git diff <1st tag> <2nd tag>
```
  
This command will differentiate between file two tags specified in input.

```
git diff <1st tag> <2nd tag> <file name>
```
  
  
  

### command to see diff between HEAD of two branch
  
This command will differentiate between all the files of two branches specified in input.

```
git diff <1st branch> <2nd branch>
```
  
This command will differentiate between file two branches specified in input.

```
git diff <1st branch> <2nd branch> <file name>
```


 
