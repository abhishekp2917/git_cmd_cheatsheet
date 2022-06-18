## command to check common base of two branches :

This command will give SHA value of the commit from where the given two branch diverges

```
git merge-base <1st branch name> <2nd branch name>
```

_________________________________________________________________________________________________________________________________


## command to rebase one branch on the tip of the branch from which it is originated :

This command will rebase current branch on the tip of the base branch given

```
git rebase <base branch name>
```

This command will rebase given branch on the tip of the base branch given

```
git rebase <base branch name> <branch name which is to be rebased>
```

_________________________________________________________________________________________________________________________________


## command to rebase one branch on the tip of the other branch :

This command will rebase given branch from the upstream branch from where the branch to be rebase originated on the tip of the base branch given

```
git rebase --onto <base branch name> <upstream branch> <branch name which is to be rebased>
```

_________________________________________________________________________________________________________________________________


## how to resolve rebase conflict :

- Run below command to abort from rebasing in case of rebase conflict

```
git rebase --abort
```

- Run below command to skip the commit of branch to be rebased which rises conflicts in case of rebase conflict

```
git rebase --skip
```

- Resolve rebase conflict manually by removing conflicting lines/ by deleting unwanted lines which cause conflicts 
  - Run below command to open conflicted file in BASH SHELL or open that file in default editor
 
  ```
  nano <file name>
  ```
  
  - Lines from '>>>>>>>>>>>>>' till '===========' shows current branch text while lines from '===========' till '<<<<<<<<<<<<<<' shows incoming branch text. 
  
  - Modify text according to requirement
 
  - Run below command to stage the changes
  
  ```
  git add .
  ```
  
  - Run below command to continue rebasing
  
  ```
  git rebase --continue
  ```
  
  - Once all the conflicts get resolved, default editor will open to enter commit message. In this way merge conflict will get resolved

_________________________________________________________________________________________________________________________________


## command to undo rebase :

This command will undo recent rebase only and will restore the SHA value of rebased branch commits

```
git reset --hard ORIG_HEAD
```

These commands will undo rebase by performing rebase opposite to rebase which is to be reversed

```
git rebase <branch name which was rebased> <base branch name>
```
```
git rebase <branch name which was rebased> <upstream of base branch> <base branch name>
```

_________________________________________________________________________________________________________________________________


## command for interactive rebase :

These commands will open the default editor showing list of commits to branch which is to be rebased so that we can drop (delete the commit)/ squash (merge the commit with previous commit and concatenate commit message)/ fixup (merge the commit with previous commit delete the commit message)/ edit (edit the files if we want to)/ reword (edit the commit message)

```
git rebase --interactive <base branch> <branch to be rebased>
``` 
```
git rebase -i <base branch> <branch to be rebased>
``` 
```
git rebase -i --onto <base branch name> <upstream branch> <branch name which is to be rebased>
```












