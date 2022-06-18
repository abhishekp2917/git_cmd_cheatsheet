## command to find which commit in the given commit range raised the bug :

To find the commit which cause the error or undesire changes follow below process

- Run below command to start the bisect process

```
git bisect start
```

- specify any one commit which has the error whose origin commit you are looking for

```
git bisect bad <SHA value/ branch name/ tag name/ HEAD/ ancestry>
```

- specify any one commit which does'nt have the error whose origin commit you are looking for

```
git bisect good <SHA value/ branch name/ tag name/ HEAD/ ancestry>
```

- Above commands will do a binary search and move the HEAD pointer to the middle of the range specified above as 'good' and 'bad'. Check the file whether that error is present or not.
 
  - Run below command if error is present
  
  ```
  git bisect bad
  ```
  - Run below command if error is not present
 
  ```
  git bisect good
  ```

- Repeat above process until you find the commit which raised the error or unwanted changes

- Run below command to come out of 'BISECTING'

```
git bisect reset
```

