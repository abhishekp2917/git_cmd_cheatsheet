## command to create tags :

This commad will create a tag at given reference

```
git tag <tag name> <SHA value/ other tag name/ branch name/ HEAD/ ancestry>
```

This command will create an annotated tag which required message

```
git tag --annotate <tag name> --message <tag message> <SHA value/ other tag name/ branch name/ HEAD/ ancestry>
```
```
git tag -a <tag name> -m <tag message> <SHA value/ other tag name/ branch name/ HEAD/ ancestry>
```

This command will create an annotated tag by opening default editor to give single/ multiple line message for the tag 

```
git tag -a <tag name> <SHA value/ other tag name/ branch name/ HEAD/ ancestry>
```

This commad will create a tag at given reference and will ovverride the tag if the tag with same name exists 

```
git tag --force <tag name> <SHA value/ other tag name/ branch name/ HEAD/ ancestry>
```
```
git tag -f <tag name> <SHA value/ other tag name/ branch name/ HEAD/ ancestry>
```

## command to view/ list tags :

These commands will show all the tags

```
git tag --list
```
```
git tag -l
```

These commands will show all the tags along with their message

```
git tag --list -n<no of lines>
```
```
git tag -l -n<no of lines>
```

## command to delete tag :

This command will delete tag based on the tag name given

```
git tag --delete <tag name>
```
```
git tag -d <tag name>
```

## command to push the tags to remote repo :

This command will push the tag given in input to remote repo

```
git push <remote name> <tag name>
```

This command will push all the tag present in local repo to remote repo

```
git push <remote name> --tags
```

## command to fetch the tags from remote repo :

This command will fetch all the tags from remote repo to local directory (repo)

```
git fetch --tags
```

## command to delete remote tags :

These command will delete remote tag given in input

```
git push <remote name> :<tag name>
```
```
git push --delete <remote name> <tag name>
```
```
git push -d <remote name> <tag name>
```
























