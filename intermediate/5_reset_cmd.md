## command to restore/ rewind the commit :

This commnad will restore the commit till the given refernce commit and move the changes to staging index

```
git reset --soft <SHA value/ tag name/ branch name/ acenstry>
```

These commnads will restore the commit till the given refernce commit and move the changes to working directory

```
git reset <SHA value/ tag name/ branch name/ acenstry>
```
```
git reset --medium <SHA value/ tag name/ branch name/ acenstry>
```

These commnads will restore the commit till the given refernce commit and delete the changes

```
git reset --hard <SHA value/ tag name/ branch name/ acenstry>
```
