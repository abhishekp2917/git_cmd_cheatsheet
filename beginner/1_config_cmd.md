## config options :

- --local :

This option is use to set configuration for current project or git respository.

```
git config --local <arguments>
```

- --global :

This option is use to set configuration which is user specific at global level.

```
git config --global <arguments>
```

- --system :

This option is use to set configuration which is at system level and applies to each repository irrespective of user.

```
git config --system <arguments>
```

__________________________________________________________________________________________________________________________________________


## view config file :

- view config file at local level which is applied to current project or git respository
 
```
cat .git/config
```

- view config file at user level which is user specific

```
cat c:\users\\.gitconfig
```

- view config file at system level which is applied to entire system/machine irrespective of user or project

```
cat c:\ProgramData\Git\config
```

__________________________________________________________________________________________________________________________________________


## config commands :

- command to set username :
```
git config --local user.name '<username>'
```

- command to set useremail :
```
git config --local user.email '<useremail>'
```

- command to set vscode as default editor :

```
git config --local user.core 'code --wait'
```

- command to enable color in UI :

```
git config --local color.ui true
```




