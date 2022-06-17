## command to merge branch :

This command will merge given branch into the current branch to which HEAD is pointing :

```
git merge <branch name>
```

This command will merge all the  given branch into the current branch to which HEAD is pointing :

```
git merge <1st branch name> <2nd branch name> <3rd branch name> <4th branch name>
```

## how to reslove merge conflicts :

- Run below command to abort/ stop merging in case of merge conflict 

```
git merge --abort
```

- Resolve merge conflict manually by removing conflicting lines/ by deleting unwanted lines which cause conflicts 
  - Run below command to open conflicted file in BASH SHELL
 
  ```
  nano <file name>
  ```
  
  - Lines from '>>>>>>>>>>>>>' till '===========' shows current branch text while lines from '===========' till '<<<<<<<<<<<<<<' shows incoming branch text. 
  
  - Modify text according to requirement
 
  - Run below command to stage the changes
  
  ```
  git add .
  ```
  
  - Run below command to continue merging
  
  ```
  git merge --continue
  ```
  
  - Once all the conflicts get resolved, default editor will open to enter commit message. In this way merge conflict will get resolved
  

- Use editor tools to resolve conflicts by accepting required changes
