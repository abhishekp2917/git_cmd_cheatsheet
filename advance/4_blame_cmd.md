## command to see commits of each line of a particular file :

This command will show very last commit ID (SHA value), author, date, time etc. that effected the specified file of each line

```
git blame <file name>
```

## 'blame' command options :

- -l 
This command will show the blame with full length SHA value

```
git blame -l <file name>
```

- -s 
This command will suppress/ hide the author name and time-stamp 

```
git blame -s <file name>
```

- --show-email/ -e
These commands will show email instead of the author name 

```
git blame --show-email <file name>
```
```
git blame -e <file name>
```
