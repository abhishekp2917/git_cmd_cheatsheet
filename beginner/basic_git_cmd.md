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

__________________________________________________________________________________________________________________________________________


## command to check status of current repo :

This will show info about current repo like what are the files which is untracked/ modified/ deleted/ staged etc.
Moreover, it also give info about any merge conflicts if arised.

```
git status
```

__________________________________________________________________________________________________________________________________________


## command to add file/ files into staging index from working directory : 

This will add specific file present in working directory into staging index

```
git add <filename.extension>
```

This will add all the files present in working directory into staging index

```
git add .
```

__________________________________________________________________________________________________________________________________________


## command to add commit : 

- Below commands will commit all the files present in staging index. It is mandatory to provide commit message for each commit.
It could be a single line or multi-line commit.

This command is for giving single-line message in git bash itself

```
git commit -m "<commit message>"
```

This command is for giving single-line/ multi-line message as it will open default editor which was set in config file earlier.

```
git commit
```

- Below commands will commit all the files present in staging index as well as working directory

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
